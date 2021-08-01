
pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "echo 'Cleaning'"
            }
        }
        stage('---Test---') {
            steps {
                sh "echo 'Testing'"
            }
        }
        stage('---package---') {
            steps {
                sh "Packaging"
            }
        }
    }
}