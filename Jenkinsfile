pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('run') {
            steps {
                echo 'Hello world!!!'
            }
        }
        stage('test') {
            steps {
                echo 'Hello world!!!'
                sh 'echo stage3'
            }
        }
    }
}