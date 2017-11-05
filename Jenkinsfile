pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }
    
  }
  stages {
    stage('node js version') {
      steps {
        sh 'node --version'
      }
    }
  }
}