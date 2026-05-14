pipeline {
    agent any

    stages {
        
        stage('Clone') {
            steps {
                echo 'Cloning Repository....'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application...'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}