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
        sh 'nppm version' // Run the script
      }
    }
    
    
  }
  
  
  
}
