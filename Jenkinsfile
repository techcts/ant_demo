pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        node(label: 'any')
      }
    }
  }
  environment {
    build = 'ant'
  }
}