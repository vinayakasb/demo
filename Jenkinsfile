pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "hello this is build stage"
'''
      }
    }

    stage('test') {
      steps {
        sh 'whoami'
      }
    }

  }
}