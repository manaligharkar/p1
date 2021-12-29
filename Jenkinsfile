pipeline {
  agent any 
    stages{
        stage("sonarqube static code check"){
            agent{
                docker{
                    image 'openjdk:11'
                    
                }
            }

            steps{
                echo 'Hello This'
                sh 'echo post action > ee.txt'
                }
            

        }
    }
}
