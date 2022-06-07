pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args 'node:6-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''npm run install
'''
      }
    }

  }
}