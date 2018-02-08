pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:smithavrasn/Hello_World.git', branch: 'master')
      }
    }
  }
}