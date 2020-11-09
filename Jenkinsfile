pipeline {
    agent any

    stages {
        stage('Build and Install') {
            steps {
                echo 'Building..'
            }
        }
        stage('Unit Testing') {
            steps {
                echo 'Testing..'
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