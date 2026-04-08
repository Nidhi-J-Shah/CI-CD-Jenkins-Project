pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('Jenkins_AI') {
                    bat 'mvn clean install'
                }
            }
        }

        stage('Test') {
            steps {
                dir('Jenkins_AI') {
                    bat 'mvn test'
                }
            }
        }
    }
}