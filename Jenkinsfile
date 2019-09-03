pipeline {

    agent any
    
    stages {
        
        stage ('Installing Dependencies') {
           steps {
                sh 'npm install'
                 }
           }
        
        stage ('Testing with Jasmine') {
           steps {
               sh 'npm install -g jasmine'
               echo 'Hello'
               sh 'jasmine'
                 }
           }
      }
}     
