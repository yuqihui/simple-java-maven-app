pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'maven:3-alpine'
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