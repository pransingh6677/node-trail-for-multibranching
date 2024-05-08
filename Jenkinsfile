pipeline {
    agent any
    parameters {
        choice(name: 'SELECTED_STAGE', choices: ['Build', 'Test', 'Deploy'], description: 'Select the stage to run')
    }
    stages {
        stage('Build') {
            when {
                expression { params.SELECTED_STAGE == 'Build' }
            }
            steps {
                // Build steps here
            }
        }
        stage('Test') {
            when {
                expression { params.SELECTED_STAGE == 'Test' }
            }
            steps {
                // Test steps here
            }
        }
        stage('Deploy') {
            when {
                expression { params.SELECTED_STAGE == 'Deploy' }
            }
            steps {
                // Deployment steps here
            }
        }
    }
}
