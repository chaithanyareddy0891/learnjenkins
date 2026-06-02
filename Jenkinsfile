pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    sh "echo 'Hello, Maven'"
                }
            }
        }
        stage('Test') {
            steps {
                script{
                    sh "echo 'Hello, JDK'"
                }
            }
        }
    }
}