pipeline {
    agent any
tools {
    maven 'maven'
  }
    stages {
        stage('Compile') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

    }
}