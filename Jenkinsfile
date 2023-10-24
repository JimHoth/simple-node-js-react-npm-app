pipeline {
    agent {
        docker {
            image 'node:18.18.2-alpine3.18' 
            args '-p 4000:4000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}