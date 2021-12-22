pipeline {

	agent any
    tools{
		maven
	}    
	stages {
		stage(build) {
			mvn clean install
			sh "build completed"		
		}
	}


}
