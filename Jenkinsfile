pipeline {
  agent any
  stages {

    stage("maven build") {
      script {
        sh 'mvn install'
      }
    }

    stage("maven package") {
      script {
        sh 'mvn package'
      }
    }

  }
}
