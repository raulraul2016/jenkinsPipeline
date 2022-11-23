pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building the core apllication'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing the apllication'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying app in OpenStack'
      }
    }

  }
}