pipeline {
    agent {
        label 'ecs'
    }
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code!!!'
                sh 'java Hello'
            }
        }
        stage('test') {
            steps {
                echo 'Running the compiled java code!!!'
                sh 'java Hello'
            }
        }
    }
}
