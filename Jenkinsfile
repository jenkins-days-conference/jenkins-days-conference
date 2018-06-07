pipeline {
  agent {
    label 'jdk9'
  }
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