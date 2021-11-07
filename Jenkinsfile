pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                sh 'chmod +x ./gradlew'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                sh './gradlew build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh './gradlew test'
            }
        }
        stage('Release') {
            steps {
                echo 'Release....'

            }
        }
    }
}