pipeline {
  agent any
  stages {
    stage('flutter status') {
      agent {
        node {
          label 'flutter'
        }

      }
      steps {
        sh 'flutter doctor'
      }
    }

  }
}