pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'          <- execute a cmd on the cmdline
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'          <- archive artifacts
            }
        }
    }
}


