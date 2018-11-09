pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Building the code'
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing the code'
                exit 1
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying the code'
            }
        }
    }
}
