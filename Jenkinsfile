pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo This is Build"
            }
        }
        stage('Test') {
            steps {
                sh "echo This is Test"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo This is Deploy"
            }
        }
    }
    post {
        always {
            echo "This section runs always"
        }
        success {
            echo "This section runs when pipeline is success"
        }
        failure {
            echo "This section runs when pipeline is failure"
        }
    }
}