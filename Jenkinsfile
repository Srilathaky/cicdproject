pipeline {
    agent any

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