pipeline {
    agent any
    
    
    stages {
        stage('my parralel') {
            parallel {
                stage('show git branch') {
                          steps {
                              echo "$GIT_BRANCH"
                          }
                }
                stage('show build number') {
                          steps {
                              echo "$BUILD_NUMBER"
                          }
                }
            }
        }
    }
}
