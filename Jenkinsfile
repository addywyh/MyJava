pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hi'
          }
        }

        stage('test') {
          steps {
            sleep 5
          }
        }

      }
    }

  }
}