node{
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
			 sh 'pwd'
		  }
		}
	   stage('Test') {
		  steps {
			  sh 'ifconfig'
		  }
		}
	}
}