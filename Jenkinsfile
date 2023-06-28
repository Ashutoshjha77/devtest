pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo $pwd'
          }
        }

        stage('test') {
          steps {
            echo 'hello world'
          }
        }

      }
    }

  }
}