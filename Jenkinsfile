pipeline {
    agent any
    stages {
        stage ('Build backend') {
            steps {
                sh 'mvn clean packege -DskipTests=true'
            }
        }
    }
}
