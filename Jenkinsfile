pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application...'
                echo 'Hello! Jenkins automatic build is working.'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
                sh 'echo Tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo Deployment completed'
            }
        }
    }
}