pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build Complited'
      }
    }

    stage('test stages ') {
      parallel {
        stage('test stages ') {
          steps {
            echo 'Complited '
          }
        }

        stage('Test1') {
          steps {
            echo 'test 1'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment Complited'
      }
    }

  }
}