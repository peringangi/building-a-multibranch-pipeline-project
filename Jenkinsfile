pipeline {
    agent {
        label "${237-master}"
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                'kubectl get nodes'
            }
        }
        stage('Test') {
            steps {
                'kubectl get nodes'
            }
        }
    }
}
