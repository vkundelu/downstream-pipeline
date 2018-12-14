pipeline {
  agent any
  stages {
    stage('Received an event') {
      steps {
        sh 'echo \'i just received a testing completed event\''
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('testing completed'))
  }
}