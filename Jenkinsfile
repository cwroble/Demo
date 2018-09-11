pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hi'
        sh 'java -version'
        archiveArtifacts artifacts: '*.sh', fingerprint: true
      }
    }
  }
} 
