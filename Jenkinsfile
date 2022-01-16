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
        stage('Running Java App') {
            steps {
                sh 'javac hello_world.java'
                sh 'java hello_world'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

