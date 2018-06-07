pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh '''npn install
npm run'''
      }
    }
  }
  environment {
    test = '1'
  }
}