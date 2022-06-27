pipeline {
    agent none
    stages {
        stage('Build'){
            agent {
                label "maven"
            }
            steps {
                sh 'ip addr'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
