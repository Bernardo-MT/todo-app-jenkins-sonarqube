pipeline {
    agent { label 'my-agent' }
    stages {
        stage('Build') {
            steps {
                echo 'Hello, World! Hello, Academy!'
            }
        }
    }
    post {
        success {
            echo 'yaay!'
        }
    }
}
