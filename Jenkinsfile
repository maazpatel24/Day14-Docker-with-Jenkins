pipeline {
    agent any

    environment {
        DOCKER = tool 'Docker-latest'
    }

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/maazpatel24/Day14-Docker-with-Jenkins.git', branch: 'master'
            }
        }
        stage('listing') [
            steps {
                script {
                    sh 'ls'
                }
            }
        ]
    }
}