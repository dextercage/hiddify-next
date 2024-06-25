pipeline {
  agent {
    node {
      label 'flutter'
    }

  }
  stages {
    stage('flutter status') {
      agent any
      steps {
        sh 'flutter build apk'
      }
    }

  }
}