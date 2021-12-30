pipeline {
    agent any
    tools { 
        maven 'M3'
        }
    stages {
        stage ('checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/manaligharkar/SpringPetClinic.git'
               
            }
        }
   
        stage ('display') {
            steps {
                sh 'echo get job soon'
            }
        }
            
       
    }
    post{
        always{
        sh 'echo post action > ee.txt'
            archiveArtifacts artifacts: '*.txt', fingerprint: true

    }
    }
}
