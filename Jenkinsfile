pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh('chmod +x gradlew')
                    sh('./gradlew --info clean')
                }
            }
        }
        stage('bie') {
            steps {
                script {
                    sh('echo goodbie!')
                }
            }
        }
    }
}
