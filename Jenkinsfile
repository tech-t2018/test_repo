pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "Another change made"'
      sh '''
        echo "This will list current dir content from latest"
        ls -lh
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO TEST"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
