pipeline {
    agent any

    stages {
        stage('Clone GitHub Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/user-prarthana/prarthana-jenkins.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Successful'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }
    }
}
