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

    post {
        always{
            echo "This section runs always"
            deleteDir()
        }
        success{
            echo "this section run when pipeline success"
        }
        failure{
            echo "this section run when pipeline failure"
        }
    }
}