pipeline {
    agent any
    stages {
	stages('clean'){
            steps {
                sh "mvn clean"
             }
	}
         stages('test'){
             steps {
                sh "mvn test"
             }
	}
         stages('package'){
              steps {
                sh "mvn package"
              }
        }
    }    
}

