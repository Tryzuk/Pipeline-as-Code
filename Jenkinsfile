pipeline {
  agent {
    docker {
      image 'maven:apline'
    }
    
  }
  stages {
    stage('Maven Version') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}