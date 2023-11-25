pipeline {    
    agent any
    stages {
        stage('Test') {
            steps {
                build 'Test_Tests'
            }
        }
        stage('Build') {
            steps {
                build 'Test_Build'
            }
        }
        stage('Deploy') {
            steps {
                build 'Test_Deploy'
            }            
            
        }
    }
}