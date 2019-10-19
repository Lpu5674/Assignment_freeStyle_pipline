pipeline {
    agent any
    stages {
        stage('Stage 1 - ISPYTHON') {
            steps {
                sh 'python --version'
            }
        }
        stage('Building') {
            steps {
                sh 'python src/calsi.py'
            }
        }
         stage('Testing') {
            steps {
                sh 'python src/calsi.py'
            }
        }
         stage('Deploying') {
            steps {
                sh 'python src/calsi.py'
            }
        }
    }
}
