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
                bat 'python sum.py'
            }
        }
    }
}
