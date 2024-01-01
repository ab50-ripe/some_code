pipeline {
  agent any
  triggers {
    cron('H/5 * * * *')
  }
  stages {
    stage('printmassage') {
      steps {
        echo 'Hello'
      }
    }

  }
}