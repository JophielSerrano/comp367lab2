pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the repository
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Use Windows commands for building
                bat 'echo Building on Windows'
                bat 'dir' // Example: Windows equivalent of 'ls'
            }
        }
        stage('Test') {
            steps {
                // Run tests using Windows commands
                bat 'echo Running tests on Windows'
            }
        }
        stage('Deploy') {
            steps {
                // Deployment steps for Windows
                bat 'echo Deploying on Windows'
            }
        }
    }
    post {
        always {
            // Cleanup or notifications
            bat 'echo Cleaning up workspace'
        }
    }
}
