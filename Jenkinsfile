pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('sleep') {
            steps {
                sleep 90
             }
          }
        stage('Unit Test') {
            steps {
                echo 'Unit Testing..'
            }
        }
        stage('Integration Test') {
            steps {
                echo 'Integration Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Monitor') {
            steps {
                echo 'Monitoring....'
             }
          }
        }
     }
