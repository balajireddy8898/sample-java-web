pipeline {
  agent any
  stages {
    stage('chekout') {
      steps {
        git(url: 'https://github.com/balajireddy8898/sample-java-web.git', branch: 'master')
      }
    }
  }
  environment {
    star = ''
  }
}