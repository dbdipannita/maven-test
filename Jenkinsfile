pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'rm -fr maven-test'
                sh 'git clone https://github.com/dbdipannita/maven-test.git'
            }
        }
        stage('Update local repo') {
            steps {
                echo 'connect to remote host and pull down the latest version'
            }
        }
    }
}
