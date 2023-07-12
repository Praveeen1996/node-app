pipeline {
    agent any
  
    stages {
        stage('CLEAN WORKSPACE') {
            steps {
                cleanWs()
            }
        }

        stage('CHECKOUT CODE') {
            steps {
                git branch: 'main', url: 'https://github.com/Praveeen1996/devops-automation.git'
            }
        }
    }
}
