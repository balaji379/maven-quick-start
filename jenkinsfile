pipeline{
    agent any
    stages{
        stage("Clone Repo"){
            steps{
                 git 'https://github.com/balaji379/maven-quick-start.git'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
        stage("Build"){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
