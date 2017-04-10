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
    stage('cccc') {
      steps {
        sh 'echo "blabal"'
        sh 'echo "blabale\''
      }
    }
    stage('ddd') {
      steps {
        echo 'hahhaha'
      }
    }
  }
}