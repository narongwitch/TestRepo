pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        echo 'Starting jenk'
      }
    }
    stage('build') {
      steps {
        build 'build TestRepo'
      }
    }
  }
}