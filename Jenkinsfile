pipeline {
  agent any
  stages {
    stage('ls') {
      steps {
        sh 'ls'
        sh 'cd download'
      }
    }
  }
  environment {
    test = '1'
  }
}