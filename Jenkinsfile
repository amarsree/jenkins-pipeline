pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                //sh 'whoami'
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
