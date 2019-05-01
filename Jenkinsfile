agent {
  docker {
   image 'ilcapone/hack-container:v01'
   args '-p 443:443'
  }
}

environment {
  CI = 'true'
}

stages {
   stage('Build') {
      steps {
         sh 'npm install'
      }
   stage('Test') {
      steps {
          sh './jenkins/scripts/test.sh
      }
    }
}