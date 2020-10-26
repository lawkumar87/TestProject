pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                git credentialsId: 'Github', url: 'https://github.com/lawkumar87/TestProject.git'
            }
        }
    }
}
