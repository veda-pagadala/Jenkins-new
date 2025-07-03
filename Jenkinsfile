pipeline {
    agent any  // Runs on any available agent (Docker/node)
    stages {
        stage('Say Hello') {
            steps {
                echo 'Hello, World!'
                sh 'echo "Hello from shell!"'  // Linux shell command
            }
        }
    }
}
