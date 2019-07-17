 piepline{
agent any
   
  stages{
     stage('compile stage'){
      steps{
           with maven(maven: 'maven 3.3.9'){
           sh 'mvn clean compile'
      }
   }
}
    stage('Testing Stage'){
      steps{
          with maven(maven: 'maven 3.3.9'){
          sh 'mvn test'
    }
  }
}
}
}
