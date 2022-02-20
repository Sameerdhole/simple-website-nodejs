pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Build') {
            steps {
                echo "building"
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying"
                sh "npm start"
            }
        }
    }
}
