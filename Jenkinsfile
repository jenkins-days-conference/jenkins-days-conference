pipeline {
  agent {
    label 'jdk8'
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