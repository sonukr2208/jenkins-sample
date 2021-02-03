pipeline {
    agent {
        node {
			label 'Linux'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'printenv'
                echo 'Building branch..'
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
