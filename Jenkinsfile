pipeline {
    agent any
    
    environment {
        GIT_REPO = 'https://github.com/kerenyashar/VS-CODE.git'
        GIT_BRANCH = 'main' 
    }

    stages {
        stage('Checkout Git Repository') {
            steps {
                // Git clone step
                git url: 'https://github.com/kerenyashar/VS-CODE.git'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
