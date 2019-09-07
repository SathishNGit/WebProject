pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'HelloPipeline1'
          }
        }
        stage('Stage2') {
          steps {
            build(job: 'HelloWorld', quietPeriod: 2)
          }
        }
      }
    }
    stage('Stage3') {
      steps {
        sleep 1
      }
    }
  }
}