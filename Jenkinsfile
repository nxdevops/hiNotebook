pipeline {
  agent any
      environment {
        SEM_VER = nextVersion()
      }
  stages {
    stage('build') {
      steps {
      sh 'echo $SEM_VER'
      }
    }

  }
}
