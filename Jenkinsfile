pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    node = '-p 3000:3000'
  }
}