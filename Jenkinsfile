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
                sh 'javac src/hello_world/Hello_world.java'
                sh 'java src/hello_world/Hello_world'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

