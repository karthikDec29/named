pipeline {
  agent any
  tools {
    Apache Maven 3.8.4
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
