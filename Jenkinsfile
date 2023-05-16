pipeline {
    agent any
    stages {
        stage('Deliver') {
            steps {
                sh '''
                 docker --version
                 docker compose up -d
                '''
            }
        }
    }
}