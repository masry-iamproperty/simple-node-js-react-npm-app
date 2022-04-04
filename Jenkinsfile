pipeline {
    agent any

    stages {
        stage("Build"){
            steps {
                echo "Building the application..."
                sh 'yarn install'
            }
        }

        stage("Test"){
            steps {
                echo "Testing the application..."
            }
        }

        stage("Deploy"){
            steps {
                echo "Deploying the application..."
            }
        }
    }
}