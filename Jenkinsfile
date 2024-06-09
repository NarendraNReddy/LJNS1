pipeline {
    agent {
        label 'AGENT-1'
    }

    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
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
                sh 'sleep 10'
            }
        }
        stage('Deploy') { 
            steps {
                sh "echo Deploy stage" 
            }
        }
    }
}