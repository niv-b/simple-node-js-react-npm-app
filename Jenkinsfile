pipeline {
  agent 'aws-test'
    
  tools {nodejs "NodeJS"}
    
  stages {
        
    stage('Git') {
      steps {
        checkout scm
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm'
      }
    }  
            
    stage('Test') {
      steps {
        echo 'tests'
      }
    }
  }
}
