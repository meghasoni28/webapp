pipeline {
    agent {
   
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
