pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('maven:alpine') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}