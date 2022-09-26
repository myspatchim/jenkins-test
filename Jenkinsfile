// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Create file multiple.txt') {
            steps {
                sh 'touch multiple.txt'
            }
        }
        stage('Add Hello') {
            steps {
                 sh 'echo "Hello" > multiple.txt'
            }
        }
        stage('Add Jenkins') {
            steps {
                 sh 'echo "Jenkins" > multiple.txt'
            }
        }
        stage('Add Workspace') {
            steps {
                 sh 'echo "Workspace" > multiple.txt'
            }
        }
        stage('show multiple.txt') {
            steps {
                 sh 'cat multiple.txt'
            }
        }
     }
}
