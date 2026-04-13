pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Ambara-joshi/ASPDotNetMVC.git'
            }
        }

        stage('Build') {
            steps {
                sh 'dotnet build'
            }
        }

        stage('Test') {
            steps {
                sh 'dotnet test'
            }
        }
    }
}
