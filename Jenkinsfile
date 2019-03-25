pipeline {
    agent any

    stages {
        stage('Checkout Source') {
            steps {
                checkout scm
            }
        }
        stage('Build Project') {
            steps {
                sh "mvn clean install"
            }
        }
    }
}