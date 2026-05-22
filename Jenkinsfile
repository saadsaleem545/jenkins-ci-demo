pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Pulling Code From GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building Application...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running Tests...'
            }
        }

        stage('Notify') {
            steps {
                sh 'echo Pipeline Executed Successfully!'
            }
        }
    }
}