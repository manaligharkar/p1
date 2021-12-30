pipeline {
  agent any 
    stages{
        stage("sonarqube static code check"){
            agent{
                docker{
                    image 'openjdk:11'
                    
                }
            }
          
            steps {
                git branch: 'main', url: 'https://github.com/manaligharkar/SpringPetClinic.git'
               
    

            steps{
                echo 'Hello This'
                sh 'echo post action > ee.txt'
                }
            

        }
    }
}
