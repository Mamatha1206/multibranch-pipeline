pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building on test branch"
                sh 'javac src/HelloWorld.java'
            }
        }
        stage('Integration Test') {
            steps {
                echo "Running integration tests"
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo "Simulating staging deployment"
            }
        }
    }
}
