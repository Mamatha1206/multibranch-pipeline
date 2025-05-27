pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building on dev branch"
                sh 'javac src/HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo "Running tests on dev branch"
            }
        }
    }
}
