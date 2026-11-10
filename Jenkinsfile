pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                checkout scm
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Execute') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
