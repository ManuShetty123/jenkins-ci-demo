pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo "Simulating a build process"'
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to staging server...'
            }
        }
    }
}
