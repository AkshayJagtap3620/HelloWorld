pipeline{
  agent any

  stages{
    stage('Build'){
      steps{
        mvn clean install
      }
    }

    stage('Execute'){
      steps{
        java -jar target/HelloWorldInJava-1.0-SNAPSHOT.jar
      }
    }
  }
}
