pipeline{
	    agent any
	    
	    stages {
	        stage ('Build Dockerfile'){
	             steps {
	                 sh (script: 'sudo docker build -t multi-pipeline .')
	             }
	         }
	     }
	 }
