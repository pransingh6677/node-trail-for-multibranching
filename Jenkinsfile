pipeline {
    agent any
    
    

    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code repository
                 sh 'echo "checkout the code from github"'
            }
        }

        stage('Install Dependencies') {
            steps {
                // Install Node.js dependencies
                sh 'echo "installing the node js dependency successfully"'
            }
        }

        stage('Unit Tests') {
            steps {
                // Run unit tests
                sh 'echo "all code are looks good"'
            }
        }

        stage('Integration Tests') {
            steps {
                // Run integration tests
                sh 'echo "tests are running integration sussessfully  "'
            }
        }

        stage('Build') {
            steps {
                // Run any build tasks if necessary
                sh 'echo "code are building"'
            }
        }

        stage('Deploy') {
            steps {
                // Use SSH to copy files to the server
                sh 'echo " hear we are deploying the code"'
            }
        }

        
    }

    
}
