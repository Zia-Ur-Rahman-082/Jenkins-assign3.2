pipeline {
    agent any
    stages {
        stage('Print IP and Hostname') {
            steps {
                script {
                    echo "This is my IP"
                    sh 'curl -s ifconfig.co'
                    echo "This is my hostname"
                    sh 'hostname -f'
                }
            }
        }
    }
}
