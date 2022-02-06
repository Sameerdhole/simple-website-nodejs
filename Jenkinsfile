pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "sudo apt -y install nodejs"
                sh "node -v"
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                sh "npm start"
            }
        }
    }
}
