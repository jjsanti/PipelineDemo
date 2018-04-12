library 'SharedLibs'
pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -v'
      }
    }
    stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
     }
  }
}
