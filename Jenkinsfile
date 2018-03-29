#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'ubuntu'
            echo "hello-hapi"
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
              
            }
        }
    }
}
