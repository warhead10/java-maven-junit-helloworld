pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
        steps {
                echo 'Running unit tests...'
            }
        }
    }
    post {
        always {
            echo 'Processing results...'
            
        }
    }
}
