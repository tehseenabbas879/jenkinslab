pipeline {
    agent any

    stages{
        stage('build') {
            steps{
                sh 'npm install'
            } 
        }
        stage('test'){
            steps{
                sh 'echo "Test is running"'
            }
        }
        stage('deploy'){
            steps{
                sh 'echo "Deploying the application"'
            }
        }
    } //build test and deploy
}
