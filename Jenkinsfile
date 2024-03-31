pipeline {
    agent any

    stages {
        stage('Install dependencies') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Execute tests') { 
            steps {
                sh 'npm test' 
            }
        }
    }
}
