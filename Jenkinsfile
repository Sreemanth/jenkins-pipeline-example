pipeline{

    agent any
    stages {
        stage('Clean'){
            steps {
                echo 'Cleaning ...'
                sh './gradlew clean'
            }
        }
        stage('Build'){
            steps {
                echo 'Build ...'
                sh './gradlew build'
            }
        }
    }
}