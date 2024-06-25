pipeline {
  agent {
    node {
      label 'flutter'
    }

  }
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