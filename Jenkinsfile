pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\\Users\\ASUS\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" --version'
            }
        }
        stage('hello') {
            steps {
                bat '"C:\\Users\\ASUS\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe" demo.py'
            }
        }
    }
}