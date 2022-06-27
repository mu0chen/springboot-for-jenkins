pipeline {
    agent none
    stages {
        stage('Build'){
            agent {
                label "maven"
            }
            steps {
                sh 'ip addr'
                sh '/opt/maven/apache-maven-3.6.3/bin/mvn -B -DskipTests clean package'
            }
        }
    }
}
