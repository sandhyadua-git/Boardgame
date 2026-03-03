pipeline {
    agent {label 'Agent1'}
     tools{
         jdk 'jdk17'
         maven 'Maven3.9.12'
     }
    stages {
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
    stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
