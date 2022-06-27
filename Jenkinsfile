pipeline {
    agent none
    stages {
        stage('Build'){
            agent {
                label "maven"
            }
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
