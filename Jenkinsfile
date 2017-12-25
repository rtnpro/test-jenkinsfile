pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "Hello world"'
            echo 'Test message'
          }
        }
        stage('stage2') {
          steps {
            sh 'echo "I\'m in stage 2"'
          }
        }
      }
    }
    stage('stage 3') {
      steps {
        echo 'Stage 3'
      }
    }
  }
}