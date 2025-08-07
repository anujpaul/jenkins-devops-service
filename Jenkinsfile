pipeline {

    agent any
    tools {
        maven 'myMaven'
    }
    stages {
        stage('Build'){
            sh 'mvn --version'
            sh 'docker --version'
            echo "Build"
        }
        stage('Release'){
            echo "released"
        }
    }
}
