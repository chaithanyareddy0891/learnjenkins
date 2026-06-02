pipeline {
    agent {
        label 'agent-1'
    }
    stages {
        stage('Build') {
            steps {
                script{
                    sh "echo 'Hello, build'"
                }
            }
        }
        stage('Test') {
            steps {
                script{
                    sh "echo 'Hello, test'"
                }
            }
        }
        stage('Deploy') {
            steps {
                script{
                    sh "echo 'Hello, Deploy'"
                }
            }
        }
    }
}