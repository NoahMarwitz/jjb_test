pipeline {
    agent { docker { image 'openjdk' } }
    stages {
        stage('build') {
            steps {
                  sh 'java -version'
            }
        }
	stage('test') {
	    steps {	
	    	  input "Test input. OK?"
	    }
	}
	stage('last') {
	    steps {
	    	  sh "echo done"	  
	    }
	}
    }
}