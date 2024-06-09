pipeline {
  agent {
    node('master')
  }
  stages {
    stage('Log hard drives status') {
      steps {
        script {
          sh 'df -h'
        }
      }
    }
  }
}