pipeline {
  agent any
  stages {
    stage('Pull latest code') {
      steps {
        bat(returnStatus: true, script: 'C:\\Project\\software\\pythonInstallDirectory\\python.exe C:\\Manish\\Personal\\Amazon\\Materials\\Python\\hello.py')
      }
    }
    stage('Build') {
      steps {
        sleep(unit: 'SECONDS', time: 10)
      }
    }
    stage('Test') {
      steps {
        echo 'Bye!'
      }
    }
    stage('Deploy') {
      steps {
        sleep 1
      }
    }
  }
}