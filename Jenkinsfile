pipeline {
    agent {
        label 'docker-agent'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Sadhika Deva - SE22UCSE230'
                echo 'Building from Jenkinsfile in Git...'
                sh 'echo Build stage complete!'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing from Jenkinsfile in Git...'
                sh 'echo Test stage complete!'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering from Jenkinsfile in Git...'
                sh 'echo Deliver stage complete!'
            }
        }
    }
}
