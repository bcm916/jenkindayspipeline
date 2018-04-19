pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'Hello'
          }
        }
      }
    }
    stage('Deploy') {
      options {
        timeout(time: 1, unit: 'MINUTES')
      }
      input {
        message 'Should we continue?'
      }
      steps {
        echo 'Continuing with deployment'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}