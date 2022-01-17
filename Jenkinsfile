pipeline {
    agent any
    
    tools{
        jdk 'jdk-11.0.13'
    }
    
    stages {
        stage('build') {
            steps {
                sh 'java -version'
                sh 'javac -version'
            }
        }
        
        stage('teste') {
            steps {
                echo 'Testing the appp.....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying the appp.....'
            }
        }
    }
}
