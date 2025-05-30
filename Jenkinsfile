pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                // This checks out the code from the Git repository
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // This runs the Maven build
                sh 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                // This runs the Maven tests
                sh 'mvn test'
            }
        }

        stage('Deliver') {
            steps {
                echo 'Delivering the application...'
            }
        }

        stage('End') {
            steps {
                echo 'Pipeline finished successfully.'
            }
        }
    }
}
