pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('mvn_ver') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}