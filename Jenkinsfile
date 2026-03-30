pipeline {
    agent {
        node {
            label 'workstation'
        }
    }
    stages {
        stage('Docker Build') {
            steps {
                sh 'docker build -t krn010/frontend .'
            }

        }

        stage('Docker Push') {
            steps {
                sh 'docker push krn010/frontend'
            }

        }

        }
    }
