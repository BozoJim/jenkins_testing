pipeline {
    agent {
        node {
            label "jenkins"
        }
    }

    stages {
        stage ("PrintEnv") {
            steps {
                sh "printenv"
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh "sleep 10"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
