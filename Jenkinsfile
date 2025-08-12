pipeline {

    agent any
    environment {
        OPENAI_API_KEY = credentials('openai-api-key-id')  // OpenAI API key injected here
    }
    tools {
        maven 'myMaven'
    }
    stages {
        stage('Build'){
            // docker run -p 8082:8081 -e AZURE_KEYVAULT_OPENAI_KEY=$OPENAI_API_KEY anujpaul/openai-spring-app
            steps{
            sh 'mvn --version'
            sh 'docker --version'
            echo "Build"
            //dsd
            }
        }
        stage('Release'){
            steps{
            echo "released"
            }
        }
    }
}
