pipeline {
  agent any
  stages {
    stage('maven install') {
      steps {
        withMaven{
        mvn clean install
        }
      }
    }

  }

}
