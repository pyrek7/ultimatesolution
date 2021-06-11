pipeline {
    agent any
    environment {
  dotnet = 'C:\\dotnet\\dotnet.exe'
              }
    stages {
        stage('Build') {
            steps {
               bat 'dotnet build --configuration Release'
            }
        }
        stage('Run') {
            steps {
                bat 'dotnet run'
            }
        }
        stage('Clean') {
            steps {
                echo 'dotnet clean'
            }
        }
    }
}