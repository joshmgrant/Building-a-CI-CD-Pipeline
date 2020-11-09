pipeline {
    agent any

    stages {
        stage('Build and Install') {
            steps {
                nodejs('12.6') { npm install }
            }
        }
        stage('Unit Testing') {
            steps {
                nodejs('12.6') { npm test }
            }
        }
        stage('Deploy Locally') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Functional Tests') {
            steps {
                echo 'WDIO Tests....'
            }
        }
        stage('Release to Product') {
            steps {
                echo 'Release....'
            }
        }
    }
}