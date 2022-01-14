pipeline {
  agent any
    
  tools {nodejs "NodeJS"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/niv-b/simple-node-js-react-npm-app.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
            
    stage('Test') {
      steps {
        echo 'tests'
      }
    }
  }
}
