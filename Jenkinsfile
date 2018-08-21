pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000 -p 5000:5000'
        }
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
               
            }
        }
        stage('Test') {
            steps {
               
            }
        }
        stage('Deliver for development') {
            when {
                branch 'development' 
            }
            steps {
              
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
               
            }
        }
        stage('Deploy for production') {
            when {
                branch 'production'  
            }
            steps {
               
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
               
            }
        }
    }
}
