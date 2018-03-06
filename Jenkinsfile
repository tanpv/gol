pipeline {
  agent {
    label 'Windows_Slave'
  }
  stages {
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}