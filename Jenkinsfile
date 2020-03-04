pipeline {
  
  agent none
  
  stages {
    
    stage('Compilation et tests') {

      agent {
        docker { image 'agent_java' }
      }     
    }
  }
}
