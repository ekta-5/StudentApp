pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Test') {
            steps {
               bat 'set PYTHONPATH=C:\\JenkinsPythonPackages && "C:\\Program Files\\Python314\\python.exe" -m pytest -v'
            }
        }
    }
}