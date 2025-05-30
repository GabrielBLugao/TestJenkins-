pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Compilando o projeto...'
                sh 'make build'
            }
        }
        stage('Test') {
            steps {
                echo 'Executando testes...'
                sh 'make test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Fazendo deploy...'
                sh 'make deploy'
            }
        }
    }
}
