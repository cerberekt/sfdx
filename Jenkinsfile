pipeline {
  agent {
    node {
      label 'sfdx-build'
    }

  }
  stages {
    stage('Dev Scratch') {
      steps {
        echo 'hello world'
      }
    }
  }
  environment {
    dev = ''
  }
}