pipeline {
  agent any
  
  tools{
    nodejs "helloNode"
  }
  
  stages {
    stage('Build') {
      steps {
        sh 'echo building_node' // Install dependencies
      }
    }
    
    stage('Run Script') {
      steps {
        sh 'npm version' // Run the script
      }
    }
    
    stage('deploy') {
      steps {
        sh 'node main.js' // Run the script
      }
    }
    
    
  }
  
  
  
}
