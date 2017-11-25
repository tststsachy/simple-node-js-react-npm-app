pipeline {
  agent {
    node {
      label 'node1'
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