pipeline {
  agent any
  stages {
    stage('get-code') {
      steps {
        git(url: 'https://github.com/gsck107/01-git-demos.git', branch: 'master')
      }
    }
  }
}