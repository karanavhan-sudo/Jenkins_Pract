pipeline {
    agent any

    stages {
        stage('environment check'){
            steps {
                sh 'node --version'
                sh 'npm --version'
            }
        }
        stage('Start') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Finish') {
            steps {
              echo 'Webhook triggered this pipeline!'
            }
        }
    }
}
