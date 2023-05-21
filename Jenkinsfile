// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Clone sources') {
            steps {
                git branch: 'main', url: '<your_git_repo>/my-todoapp.git'
            }
        }
        stage(Check file list’) {
            steps { 
                sh 'ls -l'
            }
        }
        stage('Show index.js') {
            steps { //ในโปรเจคต้องมี index.js
                sh 'cd src'
                sh 'cat index.js'
            }
        }
    }
}
