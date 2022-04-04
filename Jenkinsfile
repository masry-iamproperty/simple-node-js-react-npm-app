pipeline {
    agent any

    stages {
        stage("Build"){
            steps {
                echo "Building the application..."
                sh 'npm install'
                sh 'npm start'
            }
        }

        stage("Test"){
            steps {
                echo "Testing the application..."
                sh 'npm test'
            }
        }

        stage("Deploy"){
            steps {
                echo "Deploying the application..."
            }
        }
    }
}