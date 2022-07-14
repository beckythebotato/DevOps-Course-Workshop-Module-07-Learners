pipeline {
    agent any

    stages {
        stage('Build Dotnet') {
            steps {
                echo 'Building..'
                dotnet build
            }
        }
        stage('Test Dotnet') {
            steps {
                sh 'node --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
