pipeline {
    agent any

    stages {
        stage('run frontend') {
            steps {
                echo 'executing yarn...'
                nodeJS('Node-17-3'){
                    sh 'yarn install'
                }
                echo 'Building..'
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

