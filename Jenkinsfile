pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
      }
    }

    stage('Test Stages') {
      parallel {
        stage('Test One') {
          steps {
            echo 'Test completed'
          }
        }

        stage('Test Two') {
          steps {
            echo 'Run Test 1 completed'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'Deployment completed'
      }
    }

  }
}