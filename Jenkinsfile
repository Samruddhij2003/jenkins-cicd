pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'docker build -t jenkins-cicd:latest .'
            }
        }

        stage('Test') {
            steps {
                sh 'docker images jenkins-cicd:latest'
            }
        }

        stage('Deploy') {
            steps {
                sh 'docker stop jenkins-cicd-app || true'
                sh 'docker rm jenkins-cicd-app || true'
                sh 'docker run -d --name jenkins-cicd-app -p 8081:80 jenkins-cicd:latest'
            }
        }
    }
}