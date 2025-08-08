pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\\Users\\kabilan\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" --version'
            }
        }

        stage('hello') {
            steps {
                bat '"C:\\Users\\kabilan\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" demo.py'
            }
        }
    }
}
