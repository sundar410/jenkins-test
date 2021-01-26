pipeline {
    agent any
    
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploy'
                
            }
        }    
        stage('Build') {
            steps {
                echo 'Build'
            }   
        }
        stage('Release') {
            steps {
                echo 'Release'
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/sundar410/jenkins-test.git'
            }
        }    
    }
}
