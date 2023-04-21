pipeline {
  agent any
  stages {
    stage('connect to nfsclient') {
      steps {
        sh '''withCredentials([usernamePassword(credentialsId: \'svcdbaj \', usernameVariable: \'USER\', passwordVariable:\'PASS\'),
string(credentialsId: \'svcdbaj\', variable: \'ARTIFACTORY_AUTH\')'''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}