pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "building"
        sleep 10
      }
    }
    stage('Test') {
      steps {
        echo "testing"
        stageMessage "test stage message2"
        sleep 25
      }
    }
    stage('Deploy') {
      steps {
        echo "deploying"
        stageMessage "sample stage message"
      }
    }
  }
}
