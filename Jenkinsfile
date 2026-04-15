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
                bat '"C:\\Users\\Lenovo\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" hello.py'
            }
        }

    }
}
