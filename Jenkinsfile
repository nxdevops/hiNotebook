pipeline {
  agent any
      environment {
        NEXT_VERSION = nextVersion()
      }
  stages {
    stage('build') {
      steps {
      echo $NEXT_VERSION
      }
    }

  }
}
