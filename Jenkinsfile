pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'I\'m in checkout stage'
      }
    }
    stage('compile') {
      steps {
        echo 'I\'m in compile stage'
      }
    }
    stage('stage') {
      steps {
        echo 'I\'m in staging artifacts'
      }
    }
    stage('deploy') {
      steps {
        echo 'I\'m in deploy'
      }
    }
  }
}