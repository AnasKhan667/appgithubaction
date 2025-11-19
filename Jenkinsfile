pipeline {
    agent any
     tools {
        python 'Python3'  // ShiningPanda
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'python -m pip install --upgrade pip'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
