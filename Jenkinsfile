pipeline {
   agent any
   environment {
       color = "blue"
   }
   stages {
       stage('Code Checkout') {
            steps {
               git branch: 'master',
                credentialsId: 'GithuhSSH',
                url: 'ssh://git@test.com/proj/test_proj.git'
                sh "ls -lat"
            }
        }
    }
}
