pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/faaty-17/DevOps.git'
            }
        }
        stage('Maven') {
            steps {
                sh 'mvn --version'   // zouz tirets 9sar
            }
        }
    }
}
