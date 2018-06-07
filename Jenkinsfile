pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh '''npn install
'''
        sh 'npm run'
      }
    }
  }
  environment {
    test = '1'
  }
}