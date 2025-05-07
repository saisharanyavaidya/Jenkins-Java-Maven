pipeline {
    agent {
        label 'AGENT-1'
    }

    stages {
        stage('Checkout scm'){
            steps{
                checkout scm
                echo "success"
            }
        }
        stage(Build the application){
            steps{
                mvn clean install
            }
        }
    }
}