pipeline {
  agent {
    docker {
      image 'python:3.10-alpine'  // light, fast Python image
    }
  }
  stages {
    stage('Run Python Hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
