pipeline {
    agent any

    stages {

        stage('checkout codes ') {
            steps {
              sh 'git clone https://github.com/Savastyl/Multi-CI-CD.git'

            }
        }
        stage('build docker') {
            steps {
                echo 'building docker'
                sh 'docker build -t test-pipeline .'
            }
        }
    }
}
