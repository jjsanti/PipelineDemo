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
  }
}