pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from Git
                checkout scm
            }
        }

        stage('Run Python Script') {
            steps {
                // Run your Python script
                bat 'C:\\Users\\ranjeevkumar.pati\\AppData\\Local\\Programs\\Python\\Python311\\python.exe sum.py'
            }
        }
    }
}
