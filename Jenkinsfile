pipeline {
    agent any
    stages {
        stage('Install_requirements'){
            steps{
                sh 'pip3 install -r requirements.txt'
            }
        }
        stage('Check_endpoints') {
            steps {
                sh 'python3 check_endpoint.py'
            }
        }
    }
}
