pipeline {
    agent any
    
    stages {
        stage('Build'){
            steps {
                echo 'Building...'
                sh '''
                    docker info
                    docker compose version
                    java --version


                '''
            }
        }
    }
}