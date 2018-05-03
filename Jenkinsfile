pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        echo 'Starting'
      }
    }
    stage('S1 - Para1') {
      parallel {
        stage('S1 - Para1') {
          steps {
            echo 'S1 - Para1'
          }
        }
        stage('S1 - Para2') {
          steps {
            echo 'S1 - Para1'
          }
        }
        stage('S1 - Para3') {
          steps {
            echo 'S1 - Para3'
          }
        }
      }
    }
    stage('S2') {
      steps {
        echo 'Step 2'
      }
    }
  }
}