pipeline {
  agent any
  stages {
    stage('Say Hello - Build init') {
      steps {
        sh 'echo "Hello World - David Walton"'
        sh '''
                  echo "Multi-line works too!"
                  ls -lrtha
                '''
      }
    }
  }
}