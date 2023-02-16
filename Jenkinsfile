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
                sh "touch hello.sh"
                sh "echo 'Aalreet like hew' > hello.sh"
                sh "sh hello.sh"
            }
        }
    }
}
