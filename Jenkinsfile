pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
sh 'chmod +x script.sh; ./script.sh'
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
    }
}

