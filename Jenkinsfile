pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/balajireddy8898/sample-java-web.git', branch: 'master')
      }
    }
    stage('build') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}