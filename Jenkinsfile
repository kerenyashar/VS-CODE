pipeline {
    agent any
    
    environment {
        GIT_REPO = 'https://github.com/kerenyashar/VS-CODE.git' // Replace with your repository URL
        GIT_BRANCH = 'main' // Replace with your branch name (e.g., 'master' or 'main')
    }

    stages {
        stage('Checkout Git Repository') {
            steps {
                // Git clone step to clone the repository from the defined URL and branch
                git url: "${env.GIT_REPO}", branch: "${env.GIT_BRANCH}"
            }
        }
        
        stage('Build') {
            steps {
                // Example build step, replace with your own build process
                echo 'Building the project...'
            }
        }
        
}
