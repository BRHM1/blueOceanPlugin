pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'hello'
          }
        }

        stage('parallel build') {
          steps {
            echo 'in parallel'
          }
        }

      }
    }

  }
}