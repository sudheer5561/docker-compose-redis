pipeline{
    agent { label 'docker'}

    stages{
      
        stage('Spin-up the redis database container'){
            steps{
                script{
                    sh '''
                    docker-compose up -d

                    '''
                }
            }
        }
    }
}
