pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/wretana1294/miweb', branch: 'master')
      }
    }

    stage('list files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}