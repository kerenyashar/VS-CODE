pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/kerenyashar/VS-CODE.git'
            }
        }
    }
