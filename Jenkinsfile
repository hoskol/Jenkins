pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project... (simulated)'
            }
        }

        stage('End') {
            steps {
                echo 'Pipeline finished successfully.'
            }
        }
    }
}
