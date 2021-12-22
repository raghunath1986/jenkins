pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''
          mvn clean install
          echo "build completed"
        '''
      }
    }

  }
  tools {
    maven 'maven 3.8.4'
  }
}