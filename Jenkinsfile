pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Hello.java'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'java Hello'
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'pwd'
                echo 'Deploying....'
            }
        }
    }
}