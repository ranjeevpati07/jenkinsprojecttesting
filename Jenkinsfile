pipeline {
    agent any

    environment {
        PYTHON_PATH = 'C:\\Users\\ranjeevkumar.pati\\AppData\\Local\\Programs\\Python\\Python311\\python.exe'
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from Git
                checkout scm
            }
        }

        stage('Run Python Script') {
            steps {
                // Run your Python script using the defined variable
                bat "${PYTHON_PATH} sum.py"
            }
        }
    }
}
