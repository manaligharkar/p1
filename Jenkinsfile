pipeline {
    agent any
    
    
    stages {
        stage('my parralel') {
            parallel {
                stage('show git branch') {
                          steps {
                              echo "$GIT_BRANCH"
                              echo "Git Coomit Id : $GIT_COMMIT "
                              echo "Manali-url: $GIT_URL "
                          }
                }
                stage('show build number') {
                          steps {
                echo 'Hello, '

                sh '''

                    echo "Hello from bash"
                    echo "I am Manali "
                '''
            }
                }
            }
        }
    }
}
