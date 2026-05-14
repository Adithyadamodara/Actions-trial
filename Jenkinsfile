pipeline {
    agent any

    stages {
        
        stage('Build docker image') {
            steps {
                sh 'docker build -t ci-demo-app .'
            }
        }

        stage('Run container') {
            steps {
                sh 'docker run --rm ci-demo-app'
            }
        }
    }
}