pipeline {
  agent any
  stages {
    stage('ls') {
      steps {
        sh 'ls'
        sh '''cd Downloads

'''
        sh 'ls'
      }
    }
  }
  environment {
    test = '1'
  }
}