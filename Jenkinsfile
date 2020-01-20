pipeline {
  agent any
  stages {
    stage('Build and Run') {
      steps {
        sh 'docker-compose build'
        sh 'docker-compose up -d'
      }
    }
  }
  environment {
     PATH = "$PATH:/usr/local/bin/"
  }
}
