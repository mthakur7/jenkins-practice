@Library("Shared") _
pipeline {

  agent {
   label "ubuntuagent"
 }
  stages {
    stage('hi') {
      steps {
        sh 'echo "Hello ubuntu" >> test.txt'
      }
      
    }
    stage('make') {
      steps {
        sh "mkdir -p learndevops"
      }
      
    }
    stage("name") {
      steps { 
        script {
          hello("manjuthakur")
        }
      }
    }
      
  }
   
  
}


  
