pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git https://github.com/samyuktha-sundar/mavendemo_.git
            }
        }

        stage('Build & Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
