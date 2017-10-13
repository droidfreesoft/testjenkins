pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo '$a y $b'
      }
    }
    stage('Test') {
      agent any
      environment {
        c = 'aaaaaaa'
      }
      steps {
        echo '"$c"'
      }
    }
  }
  environment {
    a = 'Esto es una A'
    b = 'Esto es una B'
  }
}