pipeline {
  agent any
  
  tools{
    nodejs "helloNode"
  }
  
  stages {
    stage('Build') {
      steps {
        sh 'npm install' // Install dependencies
      }
    }
    
    stage('Run Script') {
      steps {
        sh 'node ./main.js' // Run the script
      }
    }
    
    
  }
  
  
  
}
