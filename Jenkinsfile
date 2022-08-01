Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'building'
            }
        }

        stage('test') {
            steps {
                echo 'testing'
            }
        }

         stage('deploying') {
            steps {
                echo 'testing'
            }
        }
    }
}