pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        powershell 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        powershell 'python3 hello.py'
      }
    }
  }
}
