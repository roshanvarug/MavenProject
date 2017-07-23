pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        parallel(
          "Stage1": {
            sh 'echo "Hello World"'
            
          },
          "Stage2": {
            sh 'echo " Hello Bangalore"'
            
          }
        )
      }
    }
    stage('Stage3') {
      steps {
        sh 'echo "Hello India"'
      }
    }
  }
}