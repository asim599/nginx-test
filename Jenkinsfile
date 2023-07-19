pipeline {
  agent any
  stages {
    stage('ssh to server') {
      steps {
        sh 'git pull '
        sh '''ssh root@192.168.1.76
'''
      }
    }

  }
}