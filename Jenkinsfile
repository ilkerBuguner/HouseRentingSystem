pipeline {
    agent any

    stages {
        stage('Restore Packages') {
            steps {
                bat 'dotnet restore'
            }
        }
        stage('Build the project') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run the tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}