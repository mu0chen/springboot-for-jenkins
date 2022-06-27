pipeline {
    agent none
    stages {
        stage('Build'){
            agent {
                label "code-build-node"
            }
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
