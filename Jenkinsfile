pipeline {
  agent any

  tools {
    maven "M3"
    jdk "JDK17"
  }

  stages {
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/tmddbs1977/spring-patclinic.git/', branch: 'main'
      }
    }
  }

}
