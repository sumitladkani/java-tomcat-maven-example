pipeline {
    agent any

    stages {
        stage('clean') {
            steps {
                bat 'mvn clean; 
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
 
