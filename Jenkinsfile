pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello world'
      }
    }
    stage('Goodbye') {
      steps {
        echo 'Goodbye!'
      }
    }
    stage('Third') {
      steps {
        sh 'java -version'
      }
    }
  }
}