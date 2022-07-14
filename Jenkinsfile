pipeline {
  agent any
  stages {
    stage("maven build") {
      steps {
        echo "installing all the maven dependencies"
        sh 'mvn install'
      }
    }

    stage("maven package") {
      steps {
        echo "generating the maven package"
        sh 'mvn package'
      }
    }
  }
}
