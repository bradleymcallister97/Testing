pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Starting"
                // Get some code from a GitHub repository
                git 'https://github.com/bradleymcallister97/Testing.git'

                sh "printenv"
                
                echo "Done"
            }
        }
    }
}
