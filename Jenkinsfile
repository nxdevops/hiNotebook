pipeline {
    agent {
        docker { image 'node:14-slim' }
    }
      environment {
        SEM_VER = nextVersion()
      }
  stages {
    stage('build') {
      steps {
      sh 'ls -lart'
      sh 'echo $SEM_VER'
      sh 'node -v'
      }
    }

  }
}
