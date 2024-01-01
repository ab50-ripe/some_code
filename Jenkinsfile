pipeline {
  agent any
  stages {
    stage('gitcheckout') {
      steps {
        git 'https://github.com/ab50-ripe/some_code.git'
      }
    }

    stage('buildit') {
      steps {
        sh '''chmod +x ./testscript.sh
./testscript.sh'''
      }
    }

  }
}