pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\Users\ASUS\viki\VikiRepo" --version'
            }
        }
        stage('hello') {
            steps {
                bat '"C:\Users\ASUS\viki\VikiRepo" demo.py'
            }
        }
    }
}