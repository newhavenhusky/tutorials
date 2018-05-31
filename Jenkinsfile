pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/newhavenhusky/tutorials', branch: 'master', changelog: true, credentialsId: 'guiYang1982', poll: true)
      }
    }
  }
  environment {
    profile = 'dev'
  }
}