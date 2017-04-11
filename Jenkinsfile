// start of pipeline
pipeline {
  // where pipeline job will run
  agent {
    label "Windows_Slave"
  }
  
  // start of stages : build, test, deploy ...
  stages {
    // start of stage : build
    stage('build') {
      // start of running steps inside one stage
      steps {
        // invoke command to build with maven
        bat 'mvn clean install'
      }
    }
  } 
}
