pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'this is my ${myvar}'
      }
    }

  }
  environment {
    myvar = '100'
    weight = '200'
  }
}