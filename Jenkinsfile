pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'checking npm version.'
                sh 'npm --version'
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
