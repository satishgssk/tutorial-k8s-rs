pipeline {
    agent any
    environment {
        YOUR_NAME=credentials("YOUR_NAME")
    }
    stages {
        stage('Deploy') {
            steps { 
                sh '''
                kubectl apply -f .
                '''
            }
        }
    }
}