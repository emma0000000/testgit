pipeline {
    agent { docker { image 'myjenkins-blueocean:2.440.3-1' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }}
