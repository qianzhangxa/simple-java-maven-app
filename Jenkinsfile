pipeline {
    agent { label 'docker' }
    tools {
        maven 'Maven_3.9.11'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
                sh 'sleep 120'
            }
        }
    }
}
