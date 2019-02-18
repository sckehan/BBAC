pipeline {
    agent any
    stages {
        stage('check out') {
                steps{
                  echo 'in the BBAC file'
                  git credentialsId: 'BBAC_user', url: 'https://github.ibm.com/bamboom/benz-npm-be'
              }
        }
    }
}
