pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "first step"'
      }
    }

    stage('build') {
      steps {
        sh 'echo "second stage"'
      }
    }

    stage('deploy') {
      steps {
        input 'do you approve ?'
      }
    }

  }
}