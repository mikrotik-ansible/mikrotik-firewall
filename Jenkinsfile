pipeline {
  agent any
  stages {
    stage('Vagrant') {
      steps {
        sh '''vagrant init dulin/mikrotik --box-version 6.37.4
vagrant up
'''
      }
    }
  }
}