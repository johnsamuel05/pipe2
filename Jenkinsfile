pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/johnsamuel05/pipe2.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac sample.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java sample'
            }
        }
    }
}
