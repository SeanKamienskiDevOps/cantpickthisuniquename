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
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should know about doing the thing?')
  }
}