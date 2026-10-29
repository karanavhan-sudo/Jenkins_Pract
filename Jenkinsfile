pipeline {
    agent any

    stages {
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
