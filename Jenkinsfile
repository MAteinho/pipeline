pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				sh gcc -o helloword.exe helloword.c
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