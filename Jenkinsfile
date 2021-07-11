pipeline {
  agent {
    node {
      label 'build'
    }

  }
  stages {
    stage('build') {
      steps {
        build(job: 'build', propagate: true, quietPeriod: 1)
      }
    }

  }
}