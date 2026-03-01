pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/RamavathSwathi-01/demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
