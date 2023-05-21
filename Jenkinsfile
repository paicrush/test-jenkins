// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Check file list') {
            steps { 
                sh 'ls -l'
            }
        }
        stage('Show index.js') {
            steps { //ในโปรเจคต้องมี index.js
                sh """
                    ls -l  
                    cat index.js
                   """
            }
        }
    }
}
