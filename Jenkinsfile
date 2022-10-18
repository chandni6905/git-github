pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                withMaven (maven : 'apache-maven-3.8.6')
                {
                bat 'mvn clean comple'    
                }

            }
        }
        stage('Test') { 
            steps {
                withMaven (maven : 'apache-maven-3.8.6')
                {
                bat 'mvn clean test'    
                }
            }
        }
        stage('Deploy') { 
            steps {
                withMaven (maven : 'maven-3.8.6')
                {
               bat 'mvn clean comple'    
                }
        }
    }
}
}