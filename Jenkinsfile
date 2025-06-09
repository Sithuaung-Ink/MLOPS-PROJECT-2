pipeline {
    agent any


    stages{

        stage("Cloning from Github...."){
            steps{
                script{
                    echo 'Cloning from Github...'
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-token-mlops2', url: 'https://github.com/Sithuaung-Ink/MLOPS-PROJECT-2.git']])
                }
            }
        }