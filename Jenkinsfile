node {
    checkout scm
    stage('Build') {
                sh '
                docker build -t jogodavelha .
                '
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}
