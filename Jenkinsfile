pipeline {
    agent { label 'slave' } // This specifies that the pipeline can run on any available agent

    stages {
        stage('Build') {
            steps {
                // Add your build steps here
                sh 'echo "Building..."'
            }
        }
        stage('Test') {
            steps {
                // Add your test steps here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Add your deployment steps here
                sh 'echo "Deploying..."'
            }
        }
    }
}
