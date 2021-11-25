node {
    checkout scm
    stage('Build') {
                sh '''
                sudo docker build jogodavelha .
                sudo docker run -i jogodavelha: /bin/bash
                '''
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}
