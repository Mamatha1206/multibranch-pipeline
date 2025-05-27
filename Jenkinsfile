pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building on prod branch"
                sh 'javac src/HelloWorld.java'
            }
        }
        stage('Final Test') {
            steps {
                echo "Running final production tests"
            }
        }
        stage('Deploy to Production') {
            steps {
                echo "Deploying to production..."
            }
        }
    }

    post {
        success {
            echo "✅ Deployment successful!"
        }
        failure {
            echo "❌ Deployment failed!"
        }
    }
}
