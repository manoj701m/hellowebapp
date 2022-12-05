pipeline{
    agent any

    tools {
         maven 'maven'
         jdk 'java'
    }

    stages{
        stage('checkout'){
            steps{
                git 'https://github.com/manoj701m/hellowebapp.git'
            }
        }
        stage('build'){
            steps{
               bat 'mvn package'
            }
        }
    }
}
