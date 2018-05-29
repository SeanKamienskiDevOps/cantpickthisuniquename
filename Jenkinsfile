pipeline {
  agent {
    node {
      label 'jdk8'
    }
    
  }
  stages {
    stage('Printable') {
      steps {
        echo "Doing The Thing, ${MY_NAME}"
      }
    }
  }
  environment {
    MY_NAME = 'Sean'
  }
}