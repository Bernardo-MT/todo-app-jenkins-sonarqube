// Basic jenkinsfile with a single stage with an echo command, using an agent called 'my-agent'
pipeline {
    agent { label 'my-agent' }
    stages {
        stage('Build') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
    post {
        success {
            echo 'yaay!'
        }
    }
}