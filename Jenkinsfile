pipeline{
    agent any
    stage{
        stage("Build") {
            steps{
                echo 'Compilando...'
            }
        }
        stage('Test'){
            steps{
                'Rodando testes'
            }

        }
        stage('Deploy') {
            steps{
                echo 'Deploy realizado com sucesso'
            }
        }
    }

}