pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/Shyamala-jai/star-week.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add deployment commands here
            }
        }
    }
}
