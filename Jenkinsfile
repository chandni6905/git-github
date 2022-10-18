pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Chandni build'
            }
        }
        stage('test') {
            steps {
                echo 'Chandni test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Chandni deploy'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}