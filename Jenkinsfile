pipeline {
    agent any
    tools {
        nodejs 'NodeJS_18'  // Ensure this matches the name in Global Tool Configuration
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
