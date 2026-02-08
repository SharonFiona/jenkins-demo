pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from Git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project from Jenkinsfile'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project from Jenkinsfile'
            }
        }
    }

    post {
        success {
            echo 'Build succeeded'
        }
        failure {
            echo 'Build failed'
        }
    }
}
