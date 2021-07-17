pipeline {
    agent {
        docker { 
            image 'node:14-alpine'
            args '-u root:root'
             }
    }
    stages {
        stage('Test') {
            steps {
                sh 'npm install --max-old-space-size=1000'
            }
        }
    }
}