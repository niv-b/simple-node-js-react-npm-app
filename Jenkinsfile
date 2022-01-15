pipeline {
  agent {
    docker { image 'node:16.3.1-alpine' }
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
