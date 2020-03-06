pipeline{
    agent { label 'docker'}

    stages{
      
        stage('Spin-up the redis database container'){
            steps{
                script{
                    sh '''
                    docker-compose -f /docker-compose-sample1/docker-compose.yml up -d

                    '''
                }
            }
        }
    }
}
