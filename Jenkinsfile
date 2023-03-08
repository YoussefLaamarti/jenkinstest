pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm install' // install dependencies
                sh 'npm run build' // run the build command
            }
        }
    }
}