pipeline {
  agent {
    docker {
      image 'openjdk'
      args '-p 8888:8080'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''cd initial
./gradlew build'''
      }
    }
    stage('Test') {
      steps {
        sh 'echo \'hoge\''
      }
    }
  }
}