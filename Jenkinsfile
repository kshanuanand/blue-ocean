pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'stage1'
          }
        }

        stage('Stage 3') {
          steps {
            echo 'Stage 3'
          }
        }

      }
    }

  }
}