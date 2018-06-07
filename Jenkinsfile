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
        sh '''pipeline {
   agent any
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }