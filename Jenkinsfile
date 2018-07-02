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
        stage('error') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('deploy1') {
      steps {
        echo 'deploy1'
      }
    }
  }
}