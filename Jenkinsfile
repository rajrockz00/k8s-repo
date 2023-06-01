pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git credentialsId: 'bitbucket', url: 'https://rajrockz00@bitbucket.org/raj00-bitbucket/devops'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing from raj branch..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
