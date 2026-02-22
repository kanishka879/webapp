pipeline {
    agent any

    stages {

        stage('Checkout SCM') {
            steps {
                git branch: 'develop',
                    url: 'https://github.com/kanishka879/webapp.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build started'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Test started'
            }
        }

    }
}
