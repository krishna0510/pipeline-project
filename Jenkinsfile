pipeline {
  agent any
  tools {
    maven 'MAVEN_HOME'
  }
  stages {
    stage('Build') {
      steps {
        sh 'make'
        archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
      }
    }
  }
}



