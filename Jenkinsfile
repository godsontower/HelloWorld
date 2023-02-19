pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building java Application'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing java Application'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying application'
      }
    }

  }
}