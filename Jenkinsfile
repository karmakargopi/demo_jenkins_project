pipeline {
    agent any
    stages {
        stage('build base image') {
            steps {
                echo 'Building Base Docker Image...'
                sh 'make build-base'
            }
        }
     }
 }
