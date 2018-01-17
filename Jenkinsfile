pipeline {
  agent {
    docker {
      image 'node:6-a;pine'
      args '-v 3000:3000'
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
