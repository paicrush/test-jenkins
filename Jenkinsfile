pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('Example') {
            environment { 
                AN_ACCESS_KEY = "my_credentails"
            }
            steps {
                sh 'printenv'
            }
        }
    }
}
