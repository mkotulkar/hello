pipeline {
  agent any
  stages {
    stage('First') {
      steps {
        echo 'Hey, there!'
      }
    }
    stage('Second') {
      steps {
        sleep(unit: 'SECONDS', time: 2)
      }
    }
    stage('Third') {
      steps {
        echo 'Bye!'
      }
    }
  }
}