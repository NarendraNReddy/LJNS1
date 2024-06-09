pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'echo build stage'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo Test stage'
            }
        }
        stage('Deploy') { 
            steps {
                sh "echo Deploy stage" 
            }
        }
    }
}