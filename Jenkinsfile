pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building simple web app'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests configured'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage placeholder'
            }
        }
    }

    post {
        success {
            echo 'Webhook pipeline executed successfully'
        }
    }
}
