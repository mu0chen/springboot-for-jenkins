pipeline {
    agent {
        label "code-build-node"
    }
    stages {
        stage('Build'){
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
