pipeline {
    agent any
  tools {
  nodejs 'NodeJS-20.4.0'
}
    stages {
        stage('CLEAN WORKSPACE') {
            steps {
                cleanWs()
            }
        }

        stage('CHECKOUT CODE') {
            steps {
                git 'https://github.com/Praveeen1996/node-app.git'
            }
        }
        stage('NODEJS BUILD CODE') {
            steps {
                sh 'npm install'
            }
        }
    }
}
