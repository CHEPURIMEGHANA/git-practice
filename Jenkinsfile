pipeline{
    agent any
    tools{
        gradle 'Gradle-8'
    }
    stages
    {
        stage('Clone from Git Repo'){
            steps{
                git branch: 'main', url: 'https://github.com/CHEPURIMEGHANA/git-practice.git'
            }
        }    
        stage('Build with Gradle'){
            steps{
                sh './gradlew build'
            }
        }
        stage('Run App'){
            steps{
                sh './gradlew run'
            }
        }
    }
}
