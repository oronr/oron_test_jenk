pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh '''npm install
'''
        sh 'npm run'
      }
    }
  }
  environment {
    test = '1'
  }
}