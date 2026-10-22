pipeline {
    agent any

    environment {
        AWS_REGION = 'ap-south-1'
        ECR_REPOSITORY = 'student-service'
        AWS_ACCOUNT_ID = '160835722395'
        IMAGE_TAG = 'latest'
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checked out from GitHub'
            }
        }

        stage('Build Docker Image') {
            steps {
                echo 'Next: build the student-service Docker image'
            }
        }

        stage('Push to AWS ECR') {
            steps {
                echo 'Next: authenticate and push the image to AWS ECR'
            }
        }
    }
}
