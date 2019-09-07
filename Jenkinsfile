pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'Build Assets'
          }
        }
        stage('Stage2') {
          steps {
            echo 'Test'
          }
        }
      }
    }
  }
}