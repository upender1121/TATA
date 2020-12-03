pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                withMaven (maven: 'maven-3.6.3'){
			  bat 'mvn build' 
                // 
            }
        }
        stage('Test') { 
               withMaven (maven: 'maven-3.6.3'){
			  bat 'mvn Test'  
                // 
            }
        }
      
      } 
    }
  }
