pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 400:4000'
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
