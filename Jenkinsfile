pipeline {
    agent any 
    stages{
        stage('git checkout'){
            steps{
                script{
                git branch: 'main', url: 'https://github.com/Shantanux/mrmrdevops_java_app.git'
                }
            }
        }
 
    }
}