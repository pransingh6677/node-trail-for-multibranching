pipeline {
    agent any
    
    parameters {
        choice(name: 'STAGE_TO_RUN', choices: ['Build', 'Test', 'Deploy'], description: 'Select stage to run')
    }
    
    stages {
        stage('Build') {
            when {
                expression { params.STAGE_TO_RUN == 'Build' }
            }
            steps {
                // Steps to build the code
            }
        }
        
        stage('Test') {
            when {
                expression { params.STAGE_TO_RUN == 'Test' }
            }
            steps {
                // Steps to run tests
            }
        }
        
        stage('Deploy') {
            when {
                expression { params.STAGE_TO_RUN == 'Deploy' }
            }
            steps {
                // Steps to deploy the application
            }
        }
    }
}
