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
                echo 'Chandni test sucessfully done'
            }
        }
        stage('infintelint') {
            steps {
                echo 'Chandni lint sucessfully'
            }
        }        
        stage('Deploy') {
            steps {
                echo 'Chandni deploy sucessfully'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}