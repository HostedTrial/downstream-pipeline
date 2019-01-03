pipeline {
  agent any
  triggers {
    eventTrigger(simpleMatch('testingCompleted'))
  }
  stages {
    stage('Received an event') {
      steps {
        echo 'I just received a testingCompleted event'
      }
    }
  }
}
