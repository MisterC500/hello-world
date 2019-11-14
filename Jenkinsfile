pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        label "lead-toolchain-skaffold"
      }
      steps {
        echo "building"
        sleep 10
      }
    }
    stage('Test') {
      agent {
        label "lead-toolchain-skaffold"
      }
      steps {
        echo "testing"
        sleep 30
      }
    }
    stage('Deploy') {
      agent {
        label "lead-toolchain-skaffold"
      }
      steps {
        echo "deploying"
        stageMessage "sample stage message"
      }
    }
  }
}
