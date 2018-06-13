pipeline {
  agent any
  stages {
    stage('First') {
      steps {
        bat(returnStatus: true, script: 'C:\\Project\\software\\pythonInstallDirectory\\python.exe C:\\Manish\\Personal\\Amazon\\Materials\\Python\\hello.py')
      }
    }
    stage('Second') {
      steps {
        sleep(unit: 'SECONDS', time: 10)
      }
    }
    stage('Third') {
      steps {
        echo 'Bye!'
      }
    }
  }
}