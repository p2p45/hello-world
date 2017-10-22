pipeline {
    agent { docker 'maven:3.3.2' }
    stages {
        stage('build') {
            steps {
                cmd 'mvn --version'
            }
        }
    }
}
