pipeline {
    agent { label 'sonarqube' }
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
