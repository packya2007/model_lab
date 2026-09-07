pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'python --version'
            }
        }

        stage('Run App') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
