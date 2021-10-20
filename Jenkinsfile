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
                url: 'ssh://git@github.com:soorajkg/demo.git'
                sh "ls -lat"
            }
        }
    }
}
