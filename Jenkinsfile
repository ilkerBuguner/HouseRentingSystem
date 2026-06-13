pipeline {
    agent any

    stages {
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