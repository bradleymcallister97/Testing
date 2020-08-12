pipeline {
    agent {
        docker { image 'bradmcallister97/jenkins_test:0.0.1' }
    }
    stages {
        stage('Build') {
            steps {
                echo "Starting"

                sh "printenv"
                
                echo "Done"
            }
        }
    }
}
