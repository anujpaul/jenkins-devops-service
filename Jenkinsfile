pipeline {

    agent any
    tools {
        maven 'myMaven'
        git 'myGit'
    }
    stages {
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
