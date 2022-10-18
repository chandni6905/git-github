pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                withMaven (maven : 'apache-maven-3.8.6')

            }
        }
        stage('Test') { 
            steps {
                withMaven (maven : 'apache-maven-3.8.6')
            }
        }
        stage('Deploy') { 
            steps {
                withMaven (maven : 'maven-3.8.6')
        }
    }
}
}