// jenkins automatically detects through polling
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build: Compiling and packaging the application using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Testing: Running unit tests with JUnit and integration tests with Selenium.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Analysing code quality using SonarQube/SonarCloud.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Scanning code vulnerabilities using Snyk or npm audit.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging: Deploying application to AWS EC2 staging server.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Staging Tests: Running integration tests in staging environment using Postman/Newman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production: Deploying final application to AWS EC2 production server.'
            }
        }
    }
}
