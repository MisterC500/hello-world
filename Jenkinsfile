pipeline {
  stages {
    stage('Build') {
      agent {
        label "lead-toolchain-skaffold"
      }
      steps {
        echo "building"
        sleep 5
      }
    }
    stage('Test') {
      agent {
        label "lead-toolchain-skaffold"
      }
      steps {
        echo "testing"
        sleep 10
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
