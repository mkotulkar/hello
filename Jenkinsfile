pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(returnStatus: true, script: 'C:\\Project\\software\\pythonInstallDirectory\\python.exe C:\\Manish\\Personal\\Amazon\\Materials\\Python\\hello.py')
      }
    }
    stage('Test') {
      steps {
        sleep(unit: 'SECONDS', time: 10)
      }
    }
    stage('Deploy') {
      steps {
        echo 'Bye!'
      }
    }
  }
}