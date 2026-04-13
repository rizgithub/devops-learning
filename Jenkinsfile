pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Executing tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'

            }
        }
    }

    environment {
        NODE_ENV = 'production'
    }

    post {
        always {
            echo 'Always post section'
        }
        success {
            echo 'Success'
        }
        failure {
            echo 'Failure'
        }
    }
}
