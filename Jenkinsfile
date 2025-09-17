pipeline{
  agent any

  tools {
        jdk 'JDK21'   // Name you configured in Jenkins JDK installations
    }

  stages{
    stage('Build'){
      steps{
        bat 'mvn clean install'
      }
    }

    stage('Execute'){
      steps{
          bat '"%JAVA_HOME%\\bin\\java.exe" -jar target/HelloWorldInJava-1.0-SNAPSHOT.jar'
'
      }
    }
  }
}
