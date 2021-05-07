pipeline {
    tools { maven 'My_Maven' }
    agent any
    stages {
        stage('Build') {
            steps {
                sh "mvn clean install"
            }
        }

        stage('Unit test') {
            steps {
                sh "mvn test"
            }
        }

    }
}
