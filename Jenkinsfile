pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Started test'
      }
    }
    stage('Build') {
      steps {
        fileExists 'package.json'
      }
    }
    stage('Deliver') {
      steps {
        echo 'Done'
      }
    }
  }
}