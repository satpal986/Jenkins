pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'Hi checkout'
      }
    }
    stage('clean') {
      steps {
        echo 'Hi clean'
      }
    }
    stage('compile') {
      steps {
        pwd(tmp: true)
      }
    }
    stage('deploy') {
      steps {
        echo 'done in deploy'
      }
    }
  }
}