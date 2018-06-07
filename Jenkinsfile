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
        echo "Hello ${MY_NAME}!"
      }
    }
    stage('Third') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}