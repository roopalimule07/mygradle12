pipeline {
  aagent any

  tools{
    gradle 'Gradle'
  }
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/roopalimule07/mygradle12.git'
      }
    }
    stages('Build') {
      steps {
        sh 'gradle build'
      }
    }
    stage('Run') {
      steps {
        sh 'gradle run'
      }
    }
  }
}
