pipeline {
  agent any
  stages {
    stage('Pull latest code') {
      steps {
        echo 'Get latest code from Git'
      }
    }
    stage('Build') {
      steps {
        echo 'Code compilation activity started.'
        bat 'C:\\Project\\software\\pythonInstallDirectory\\python.exe C:\\Manish\\Personal\\Amazon\\Materials\\Python\\chdir.py'
        bat(script: 'mvn compile', returnStatus: true)
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