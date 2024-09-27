pipeline {
    agent { docker { image 'python:3.12.1-alpine3.19' } }
    stages {
        stage('Build') {
            steps {
                echo 'Building the project.'
                }
            }
        stage('Test') {
            steps {
                echo 'Running tests.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application.'
            }
        }
    }
post {
        always {
            echo 'Will always run, irrespective of success or failure'
        }
    }
}
