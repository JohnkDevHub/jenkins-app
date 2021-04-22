
pipeline{
	agent any
	
	stages{
		stage("Build"){
			steps{
				sh "mvn -version"
				
			}
		}
	}
	
	post{
		always{
			echo 'OK then'
		}
	}	
	
}



