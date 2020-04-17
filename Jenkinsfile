pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                git credentialsId: 'github', url: 'https://github.com/verma1997/git-test.git'
            }    
        }
    }
}