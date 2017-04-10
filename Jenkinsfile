pipeline {
  agent any
  stages {
    stage('next') {
      steps {
        parallel(
          "next": {
            sh 'echo "next"'
            
          },
          "test": {
            echo 'test'
            
          }
        )
      }
    }
  }
}