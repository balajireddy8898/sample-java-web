pipeline {
  agent any
  stages {
    stage('chekout') {
      steps {
        git(url: 'https://github.com/balajireddy8898/sample-java-web.git', branch: 'master')
      }
    }
    stage('build') {
      steps {
        bat(returnStatus: true, script: 'mvn clean install')
      }
    }
    stage('sonarqueb') {
      steps {
        bat 'mvn sonar:sonar'
      }
    }
  }
  environment {
    star = ''
  }
}
