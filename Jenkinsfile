pipeline{
    agent any
    stages{
        stage('Git Checkout with master'){
            when {
                branch 'master'
            }
            steps{
                git credentialsId: 'github', url: 'https://github.com/verma1997/git-test.git'
            }    
        }
        stage('Final Step with priyanshu'){
            when {
                branch 'priyanshu'
            }
            steps{
                git credentialsId: 'github', url: 'https://github.com/verma1997/git-test.git'
            }
        }
    }
}
