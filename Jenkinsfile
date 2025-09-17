pipeline{
  agent any

  stages{
    stage('Build'){
      steps{
        bat 'mvn clean install'
      }
    }

    stage('Execute'){
      steps{
        bat 'java -jar target/HelloWorldInJava-1.0-SNAPSHOT.jar'
      }
    }
  }
}
