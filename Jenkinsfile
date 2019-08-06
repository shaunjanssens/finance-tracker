pipeline {
  agent {
    docker {
      image 'node:6.3'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'npm --version'
      }
    }
  }
}