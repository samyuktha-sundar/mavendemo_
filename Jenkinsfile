pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/your-friend-username/mavendemo.git'
            }
        }

        stage('Build & Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
