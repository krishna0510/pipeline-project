pipeline {
    agent any
    tools {
    maven 'MAVEN_HOME'
  }
    stages {
        stage('Build') {
            steps {
                sh 'mvn build'
            }
        }
        stage('Test') {
            steps {
                sh 'test'
            }
        }
        stage('package') {
            steps {
                echo 'mvn package'
            }
        }
    }
}


