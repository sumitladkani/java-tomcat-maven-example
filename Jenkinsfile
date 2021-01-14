pipeline {
    agent any

    stages {
        stage('clean') {
            steps {
                bat 'mvnclean; 
         }
        }
        stage('test'){
            steps{
                bat 'mvn test';
         }        
        }     
        stage ('build') {
             steps{
                    bat 'mvn package'
       }            
      }
    }
}
 
