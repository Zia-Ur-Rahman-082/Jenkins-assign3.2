pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Application build stage...'
            }
        }
        stage('Test') {
            steps {
                echo 'Application test stage'
            }
        }
        stage('Run') {
            steps {
                echo 'Application run stage'
                bat 'python sample_code.py' // Use 'bat' for Windows
            }
        }
    }
}
