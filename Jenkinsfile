pipeline {
    agent any
    environment { 
        CC = 'clang'
        ENV-JENKINS ='env.BUILD_NUMBER'
        ENV-JENKINS-1 ="env.BUILD_NUMBER"

    }
    stages {
        stage('Example') {
            environment { 
                AN_ACCESS_KEY = "my_credentails"
            }
            steps {
                sh 'echo ${env.ENV-JENKINS}'
				sh 'echo ${env.ENV-JENKINS-1}'
                sh 'printenv'
            }
        }
    }
}
