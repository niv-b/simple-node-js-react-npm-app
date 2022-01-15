pipeline {
  agent {
    docker { image 'python' }
}
        
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
