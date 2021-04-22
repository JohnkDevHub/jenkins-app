
pipeline{
	agent any
	
	tools{
		maven "3.6.3"
	}
	
	stages{
		stage("Display Version "){
			steps{
				sh "mvn -version"
			}
		}
		
		stage("Do Build"){
			steps{
				sh "mvn clean install"
			}
		}
	}
	
	post{
		always{
		echo 'nice one'
			cleanWs()
		}
	}	
	
}


