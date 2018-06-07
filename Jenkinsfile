pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh '''npm install
'''
          }
        }
        stage('npm serve') {
          steps {
            sh 'nmp serve'
          }
        }
      }
    }
  }
  environment {
    test = '1'
  }
}