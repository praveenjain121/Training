pipeline {
    agent none 
    stages {
        stage('Build') {
           // agent { docker 'maven:3.8.6-eclipse-temurin-11' } 
            steps {
                echo 'Hello, Maven'
                bat 'java -version'
               // mvn --version
            }
        }
        stage('Test') {
           // agent { docker 'openjdk:8-jre' } 
            steps {
                echo 'Hello, JDK'
                echo java -version
            }
        }
    }
}
