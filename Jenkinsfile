pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/shilpasivadasan/webfiles.git', branch: 'main', credentialsId: 'stage1')
      }
    }

  }
}