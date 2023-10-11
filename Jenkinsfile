pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('First') {
            steps {
                sh 'cd ~/test/lighthouse-role'
                sh 'ls -l'
            }
        }
    }
}
