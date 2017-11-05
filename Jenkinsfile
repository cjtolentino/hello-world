pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''ls -lrt
cat README.md
'''
      }
    }
  }
  environment {
    uat = 'uat'
  }
}