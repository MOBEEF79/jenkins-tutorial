pipeline {
    agent any
    stages {
        stage('Stage 1 List Files'){
            steps {
                sh "ls -la"
            }
        }
        stage('Stage 2 Create Files'){
            steps {
                sh "mkdir newfiles"
                sh "ls -la"
                sh "cd newfiles"
                sh "touch hello.sh"
                sh "ls -la"
            }
        }
    }
}
