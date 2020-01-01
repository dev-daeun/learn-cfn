pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        build(job: 'init', quietPeriod: 1)
      }
    }

  }
}