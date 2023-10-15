pipeline {
    agent {
        docker {
            image 'node:16' // Use Node.js 16 Docker image as the build agent
        }
    }
    stages {
        stage('Build') {
            steps {
                script {
                    // Run 'npm install --save' to install project dependencies
                    sh 'npm install --save'
                }
            }
        }
    }
}
