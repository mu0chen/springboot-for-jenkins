pipeline {
    agent none
    stages {
        stage('Build'){
            agent {
                label "maven"
            }
            steps {
                sh 'echo which mvn'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
