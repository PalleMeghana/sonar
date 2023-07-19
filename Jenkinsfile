pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Sonar scanning') {
            steps {
                echo 'Scanning the quality of code'
            }
        }
        stage('Publish to Artifactory') {
            steps {
                echo 'Publishing to Artifactory'
            }
        }    
        stage('Deploy to Dev') {
            steps {
                echo 'Deploying to Dev'
            }
        }
        stage('Deploy to UAT') {
            steps {
                echo 'Deploying to UAT'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy to Artifactory') {
            steps {
                echo 'Deploy to Artifactory'
            }
        }
    }
}
