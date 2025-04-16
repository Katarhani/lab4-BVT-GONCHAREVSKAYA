pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Katarhani/lab5.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
