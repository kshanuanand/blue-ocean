pipeline {
  agent any
  stages {
    stage('Series and Parallel Test') {
      parallel {
        stage('Stage 1') {
          steps {
            bat 'stage1'
          }
        }

        stage('Stage 3') {
          steps {
            bat 'Stage 3'
          }
        }

      }
    }

  }
}
