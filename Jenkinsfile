pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "Build sample-book-app"
            }
        }
        stage('deploy-dev') {
            steps {
                echo "Deployment triggered to DEV env"
            }
        }
        stage('api-test-dev') {
            steps {
                echo "Executing api tests against DEV env"
            }
        }
        stage('deploy-stg') {
            steps {
                echo "Deployment triggered to STG env"
            }
        }
        stage('api-test-stg') {
            steps {
                echo "Executing api tests against STG env"
            }
        }
        stage('deploy-prd') {
            steps {
                echo "Deployment triggered to PRD env"
            }
        }
        stage('api-test-prd') {
            steps {
                echo "Executing api tests against PRD env"
            }
        }
    }
}
