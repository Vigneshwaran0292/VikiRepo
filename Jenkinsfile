pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat ' "C:\\Users\\ASUS\\AppData\\Local\\Programs\\Python\\Python313\\python.exe python --version'
            }
        }
        stage('hello'){
            steps{
                bat ' "C:\\Users\\ASUS\\AppData\\Local\\Programs\\Python\\Python313\\python.exe demo.py'
            }
        }
    }
}