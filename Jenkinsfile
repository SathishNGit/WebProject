pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Build Assets') {
          steps {
            echo 'Build Assets'
          }
        }
        stage('Test') {
          steps {
            echo 'Test'
          }
        }
      }
    }
  }
}