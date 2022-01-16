pipeline {
    agent any

    stages {
        stage('run frontend') {
            steps {
                echo 'executing yarn...'
                nodejs('Node-10.17'){
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

