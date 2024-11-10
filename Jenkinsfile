pipeline {
    agent any 
    environment {
        AWS_SECRET_ACCESS_KEY = credentials ('AWS_SECRET_ACCESS_KEY')
        AWS_ACCESS_KEY_ID =  credentials ('AWS_ACCESS_KEY_ID')
        students = '123456'
    }
    
    stages {
        stage ('show environment') {
            steps {
                sh 'env'
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