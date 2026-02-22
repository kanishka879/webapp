pipeline {
    agent any

    stages {

        stage('Checkout SCM') {
            steps {
                git 'git@github.com:kanishka879/webapp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

    }
}
