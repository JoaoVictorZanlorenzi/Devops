node {
    checkout scm
    stage('Build') {
                sh '''
                sudo docker build jogodavelha .
                sudo docker run jogodavelha:latest /bin/bash
                '''
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}
