pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Repository checked out successfully'
            }
        }

        stage('Run Python Program') {
            steps {
                bat 'python calc.py'
            }
        }

        stage('Completed') {
            steps {
                echo 'Pipeline executed successfully!'
            }
        }
    }
}
