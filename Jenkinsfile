pipeline {
    agent any 
    environment {
        AWS_SECRET_ACCESS_KEY = credentials ('AWS_SECRET_ACCESS_KEY')
        AWS_ACCESS_KEY_ID =  credentials ('AWS_ACCESS_KEY_ID')
    }
    
    stages {
        stage ('First stage') {
            steps {
                echo ' this is stage one '
            }
        }
        stage ('Second stage') {
            steps {
                echo 'this is stage two'
                echo 'it is the second stage'
            }
        }
    }
}