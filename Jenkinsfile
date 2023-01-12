pipeline {
    agent any

    stages {
        stage('Scm Checkout') {
            steps {
                echo 'this is the checkout stage'
                sh 'sleep 5'
            }
        } 
        stage('BUIlD') {
            steps {
                echo 'this is the build stage '
                sh 'sleep 5'
                
            }
        }  
        stage('push') {
            steps {
                echo 'this is the artifactory stage '
                sh 'sleep 5'
                
            }
        }  
        stage('Deploy') {
            steps {
                echo 'this is the deploy stage '
                sh 'sleep 5'
                
            }
        }  
        stage('Test') {
            steps {
                echo 'this is the test stage '
                sh 'sleep 5'
                
            }
        }  
    }
}
