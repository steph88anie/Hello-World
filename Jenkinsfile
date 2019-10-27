pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Build the hello world app here.'
      }
    }
    stage('Buzz Unit Tests') {
      steps {
        echo 'Run unit tests'
      }
    }
    stage('Buzz Regression Tests') {
      steps {
        echo 'Run Regression Tests'
        echo 'Publish XML tests to JUnit'
        echo 'Send email notifications if the tests fails'
      }
    }
  }
}