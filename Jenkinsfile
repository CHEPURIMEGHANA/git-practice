pipeline{
    agent any
    stages
    {
        stage('Clone from Git Repo'){
            steps{
                git branch: 'main', url: 'https://github.com/CHEPURIMEGHANA/git-practice.git'
            }
        }    
        stage('Print msg'){
            steps{
                echo 'Hello from declarative pipeline'
            }
        }
    }
