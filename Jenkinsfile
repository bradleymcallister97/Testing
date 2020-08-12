pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Starting"

                sh "printenv"

                def myImage = docker.build("bradmcallister97/jenkins_test:0.0.1")

                myImage.inside {
                    sh '/nightfall_dlp'
                }
                
                echo "Done"
            }
        }
    }
}
