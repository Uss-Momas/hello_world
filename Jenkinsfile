pipeline {
    agent any
    
    tools{
        jdk 'jdk-11.0.13'
    }
    
    stages {
        stage('Java-version') {
            steps {
                sh 'java -version'
                sh 'javac -version'
            }
        }
        
        stage('Build-compile and Run') {
            steps { 
                sh 'javac hello_world.java'
                sh 'java hello_world'
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
                echo 'Succeed....'
            }
        }
    }
}
