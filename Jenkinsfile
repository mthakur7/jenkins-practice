pipeline {

  agent {
   label "ubuntuagent"
 }
  stages {
    stage('hi') {
      steps {
        echo "Hello ubuntu" >> test.txt
      }
      
    }
    stage('make') {
      steps {
        sh "mkdir -p learndevops"
      }
      
    }
      
  }
   
  
}


  
