pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Difference between echo and sh"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
