pipeline {
  agent {
    node {
      label 'node:6-alpine'
    }
    
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}