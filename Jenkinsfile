pipeline {
    agent any
    environment {
  gg = 'C:\\Program Files\\dotnet\\dotnet.exe'
              }
    stages {
        stage('Build') {
            steps {
               bat 'gg build --configuration Release'
            }
        }
        stage('Run') {
            steps {
                bat 'gg run'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}