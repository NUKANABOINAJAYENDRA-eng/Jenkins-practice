pipeline {
    agent {
        label 'Agent-kp83'
    }
    stages {
        stage('build') {
            steps {
                sh 'echo this is a build stage'
            }
        } 
        stage('test') {
            steps {
                sh 'echo this is tessting stage'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo this is deploying stage'
            }
        }
    }
}