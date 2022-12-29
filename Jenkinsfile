pipeline {
    agent none 
    stages {
        stage('Example Build') {
           // agent { docker 'maven:3.8.6-eclipse-temurin-11' } 
            steps {
                echo 'Hello, Maven'
                java -version
               // mvn --version
            }
        }
        stage('Example Test') {
           // agent { docker 'openjdk:8-jre' } 
            steps {
                echo 'Hello, JDK'
                java -version
            }
        }
    }
}
