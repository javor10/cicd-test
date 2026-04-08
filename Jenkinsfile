pipeline { 
	agent any
		
	stages {
	  stage('Github pull') {
	    steps {
	      git branch: 'main',url:'https://github.com/javor10/cicd-test.git'
	    }
	  }
	  stage('Git clone end') {
	    steps {
	    sh 'touch cicd_test.txt'
	    sh 'echo "git clone end22" > cicd_test.txt'
	    }
	  }
	}


