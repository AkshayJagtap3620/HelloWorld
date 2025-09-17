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
        bat '"C:\Program Files\Java\jdk-21\bin\java.exe" -jar target/HelloWorldInJava-1.0-SNAPSHOT.jar'
'
      }
    }
  }
}
