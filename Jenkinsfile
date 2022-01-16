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
        stage('Compiling') {
            steps {
                sh 'javac hello_world.java'
            }
        }
        stage('Running') {
            steps {
                sh 'java hello_world'
            }
        }
    }
}

