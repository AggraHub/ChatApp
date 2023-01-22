pipeline {
agent any
environment {
}
  stages {
    stage('Build') {
      steps {
        sh 'docker compose build'
      }
    }
    stage('Deploy') {
       steps {
         sh 'docker compose up -d'
       }
    }
  }
}