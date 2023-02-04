pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
          with maven {
        sh 'mvn clean install'
}
      }
    }

  }
}
