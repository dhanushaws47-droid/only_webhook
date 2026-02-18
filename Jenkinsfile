pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Triggered from GitHub push!"
                sh 'echo Hello from GitHub Webhook'
            }
        }
    }
}
