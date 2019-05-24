pipeline {
  agent any
  parameters {
    gitParameter branchFilter: 'origin/(.*)', defaultValue: 'master', name: 'BRANCH', type: 'PT_BRANCH'
  }
  stages {
    stage('build') {
      steps {
        echo 'Hello world from Jenkins!!'
        sh '''uname -a
whoami
pwd'''
      }
    }
  }
}