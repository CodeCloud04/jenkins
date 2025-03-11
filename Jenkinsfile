pipeline {
    agent any  // Runs on any available Jenkins agent

    stages {
        stage('Initialize') {
            steps {
                echo 'Starting Jenkins pipeline...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo Simulating build process'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Simulating test execution'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo Simulating deployment'
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Cleaning up resources...'
                sh 'echo Simulating cleanup'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution finished!'
        }
        success {
            echo 'Pipeline completed successfully! ✅'
        }
        failure {
            echo 'Pipeline failed! ❌'
        }
    }
}
