pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-P'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
