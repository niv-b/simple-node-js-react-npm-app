pipeline {
  agent {
    node {
        label 'aws-test'
    }
}
    
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
