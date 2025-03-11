pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Test Start') {
            steps {
                echo 'Hello, Jenkins! Pipeline is running...'
            }
        }

        stage('Check System Info') {
            steps {
                sh 'uname -a'  // Runs a basic system info command
            }
        }

        stage('Success') {
            steps {
                echo 'Jenkins test pipeline executed successfully!'
            }
        }
    }
}
