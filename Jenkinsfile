pipeline {
  agent any
  stages {
    stage('maven install') {
      steps {
        withMaven(maven: 'MAVEN'){
        mvn clean install
        }
      }
    }

  }

}
