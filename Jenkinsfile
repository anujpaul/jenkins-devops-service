pipeline {

    agent any
    tools {
        maven 'myMaven'
     //   git 'myGit'
    }
    stages {
        stage('Checkout'){
            steps{
                git branch 'main', url: 'https://github.com/anujpaul/jenkins-devops-service.git'
            }
        }
        stage('Build'){
            steps{
            sh 'mvn --version'
            sh 'docker --version'
            echo "Build"
            }
        }
        stage('Release'){
            steps{
            echo "released"
            }
        }
    }
}
