pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'jenkins', url: 'https://github.com/Arjun-gitlab/GeneralSpringBootProgExce.git'
                sh 'mvn clean package'
            }
        }
    }
}
