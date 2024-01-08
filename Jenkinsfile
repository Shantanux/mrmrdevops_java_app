@Librare('jenkins-shared-library') _

pipeline {
    agent any 
    stages{
        stage('git checkout'){
            steps{
                script{
                    gitCheckout{
                    
                git branch: 'main',
                url: 'https://github.com/Shantanux/mrmrdevops_java_app.git'
                    }
                }
            }
        }
 
    }
}