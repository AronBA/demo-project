pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/AronBA/demo-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Building the application...'
            }
        }
    }

    post {
        success {
            echo 'Build and tests passed successfully!'
        }
        failure {
            echo 'Build failed. Check logs for details.'
        }
    }
}
