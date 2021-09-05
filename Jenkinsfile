pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '4fe45e35-9e86-485a-bf1e-45f599370f4a', url: 'https://github.com/rishing1992/Jenkins.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build Log'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
