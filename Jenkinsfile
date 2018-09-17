pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh '''
                    sleep 1
                    echo your mom
                    mvn --version
                '''
            }
        }
    }
}
