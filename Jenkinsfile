pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('environment') {
            steps {
                sh 'echo $JAVA_HOME'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}