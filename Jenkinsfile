node('master'){
	stage('SCM checkout'){
	
		git 'https://github.com/Rajeevdevops/Java-jenkins'
	
	}
	
	stage('compile package'){
		
		def mvnhome = tool name: 'Maven-3', type: 'maven'	
		sh "${mvnhome}/bin/mvn package "
	}
}



