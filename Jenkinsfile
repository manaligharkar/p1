pipeline {
    agent any
    tools { 
        maven 'M3'
        }
    stages {

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
