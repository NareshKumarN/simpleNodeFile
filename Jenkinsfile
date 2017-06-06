pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh ‘nodemon node.js’
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}