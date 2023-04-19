pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { lavel 'nodejs-app' }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
