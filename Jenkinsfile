pipeline {
  agent any
  tools{
      gradle 'gradle6'
  }
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh 'gradle --version'
      }
    }
  }
}
