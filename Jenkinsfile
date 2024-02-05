pipeline {

    agent any
    stages {
        stage('Build') {
            sh "echo testing"
            sh 'python --version'
        }
        stage('Test') {
            sh 'python -m pytest'
        }

    }
}

