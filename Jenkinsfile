pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building branch..'
                sh 'printenv'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing branch..'
            }
        }
        stage('Publish') {
            steps {
                echo 'Publish branch....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying branch....'
            }
        }
    }
}
