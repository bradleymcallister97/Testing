pipeline {
    agent {
        docker { image 'nightfallai/nightfall_dlp:1088f8f8e7fbab98aaa8b2929b69b700f16044b7' }
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
