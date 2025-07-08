pipeline{
    agent any

    stages{
        stage("Cloning from GitHub..."){
            steps{
                script{
                    echo 'Cloning from GitHub...'
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-token', url: 'https://github.com/htasoftware99/Anime_Recommendation_System.git']])
                }
            }
        }
    }
}