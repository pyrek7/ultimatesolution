pipeline {
    agent any
    environment {
        gg = 'C:\\Program Files\\dotnet\\dotnet.exe'
    }
    stages {
        stage('Build') {
            steps {
               echo "Hello ${env.gg}"
            }
        }
        stage('Run') {
            steps {
                echo "Hello ${env.gg}"
            }
        }
        stage('Deploy') {
            steps {
               echo "Hello ${env.gg}"
            }
        }
    }
}