pipeline {
    agent any

    stages {
        stage('Docker Build') {
            steps {
                git branch: 'main', url: 'https://github.com/rmachineedi/navya.git'
            }
        }
    }
}
