pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build the app'
      }
    }
    stage('test ') {
      steps {
        echo 'delivering to qa'
      }
    }
    stage('delivery') {
      steps {
        retry(count: 2)
      }
    }
  }
}