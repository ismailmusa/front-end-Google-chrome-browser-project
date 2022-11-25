pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                archiveArtifacts artifacts: 'index.html'
                echo 'Deploying....'
            }
        }
    }
}
