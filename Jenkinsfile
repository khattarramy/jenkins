pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            echo 'ramy'
          }
        }
        stage('') {
          steps {
            echo 'test'
          }
        }
      }
    }
  }
}