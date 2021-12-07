pipeline {
  agent any
      environment {
        NEXT_VERSION = nextVersion()
      }
  stages {
    stage('build') {
      steps {
      sh 'echo $NEXT_VERSION'
      }
    }

  }
}
