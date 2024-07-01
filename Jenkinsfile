pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'git code'
        git(url: 'https://github.com/kevinlmxy/spring2.git', branch: 'main')
        build 'spring'
        sh '''ls
uptime'''
      }
    }

  }
}