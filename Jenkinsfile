pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Building on Windows...'
                // Add other Windows-compatible build commands here
            }
        }
    }

    post {
        success {
            bat 'echo ✅ Build was successful on Windows!'
        }
        failure {
            bat 'echo ❌ Build failed on Windows!'
        }
    }
}
