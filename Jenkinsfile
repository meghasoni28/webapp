pipeline {
    agent {
   
    }
    stages {
        stage('Build') {
            steps {
               echo "HEllo build"
            }
        }
        stage('Test') {
            steps {
               echo "hello test"
            }
        }
        stage('Deliver for development') {
            when {
                branch 'development' 
            }
            steps {
              
                echo "hello deploy"
               
            }
        }
        stage('Deploy for production') {
            when {
                branch 'production'  
            }
            steps {
               
                echo "hello prod"
               
            }
        }
    }
}
