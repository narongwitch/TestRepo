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
        build(job: 'build TestRepo', propagate: true, quietPeriod: -1)
      }
    }
  }
}