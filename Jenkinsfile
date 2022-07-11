pipeline {
    agent any

    stages {
        stage('Docker Build') {
            steps {
                bat 'docker-compose -f Docker-compose.yml up -d'
            }
        }
    }
}
