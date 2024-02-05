pipeline {
  agent any
  tools {
    maven:latest
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
