pipeline {
    agent any

    tools {
        jdk 'Jdk17'
        maven 'Maven3'
    }

    stages {
        stage("Build") {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
