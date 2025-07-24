pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from GitHub!'
            }
        }

        stage('Run Tests') {
            steps {
                echo '✅ Running unit tests...'
                // Yahan actual test command aayegi e.g., npm test / pytest
                sh 'echo "All tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying to staging...'
                // Dummy deploy simulation
                sh 'echo "Deployment done!"'
            }
        }
    }
}
