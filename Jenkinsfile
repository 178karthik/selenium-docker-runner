pipeline{

    agent any

    stages{
        stage('Run Test'){
            steps{
                bat "docker-compose up"
            }
        }
         stage('Bring Grid Down'){
            steps{
               bat "docker-compose down"
        }
         }
         stage('stage-3'){
            steps{
            echo "pushing docker image"
        }

         }
    }
}