pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage ("wait_prior_starting_smoke_testing") {
    def time = params.SLEEP_TIME_IN_SECONDS
    echo "Waiting ${SLEEP_TIME_IN_SECONDS} seconds for deployment to complete prior starting smoke testing"
    sleep time.toInteger() // seconds
        }
     }
 }
