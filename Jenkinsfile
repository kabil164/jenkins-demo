pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/kabil164/jenkins-demo.git'
            }
        }

        stage('Run Code') {
            steps {
                bat 'hello.py'
            }
        }

    }
}
