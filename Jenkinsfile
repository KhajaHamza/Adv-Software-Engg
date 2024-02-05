pipeline {

    agent any
    stages {
        stage('Setup') {
            sh "echo testing"
            sh 'python --version'
            sh 'pip install -r requirements.txt'
        }
        stage('Test') {
            sh 'python -m pytest'
        }

    }
}

