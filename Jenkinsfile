pipeline {
    agent any

    stages {
        stage('Setup'){
            steps {
                sh 'npm install'
            }
        }
        stage('Test'){
            steps {
                sh 'NO_COLOR=1 npm run cy:run-ci'
            }
        }
    }

}