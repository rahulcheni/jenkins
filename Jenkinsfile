pipeline {
    agent any
        }
    stages {
        stage("clone code"){
            steps{
               git credentialsId: 'git_credentials', url: 'https://github.com/rahulcheni/jenkins.git'
            }
        }
        stage("build code"){
            steps{
              sh "mvn clean install"
            }
        }
    
            }
        }
    }
}
