pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                bat 'dotnet build' // Ou use 'sh' se estiver no Linux
            }
        }
        
        stage('Move to E:\\Teste') {
            steps {
                bat 'move <caminho\\do\\arquivo> E:\\Teste' // Ou use 'mv' se estiver no Linux
            }
        }
    }
}
