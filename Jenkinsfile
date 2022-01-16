pipeline {
    agent any
    
    tools{
        jdk 'jdk-11.0.13'
    }

    stages {
        stage('java-11') {
            steps {
                sh 'java -version'
                sh 'javac -version'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

