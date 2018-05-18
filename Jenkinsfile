pipeline {
  agent any
  stages {
    stage('Print') {
      steps {
        echo 'Done'
      }
    }
    stage('error') {
      steps {
        waitUntil() {
          sleep 10
        }

      }
    }
  }
}