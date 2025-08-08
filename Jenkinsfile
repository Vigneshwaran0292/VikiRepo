pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\Windows\System32\cmd.exe" --version'
            }
        }
        stage('hello') {
            steps {
                bat '"C:\Windows\System32\cmd.exe" demo.py'
            }
        }
    }
}