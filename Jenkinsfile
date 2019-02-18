pipeline {
	agent any

	stages {
	  stage('Print') {
      steps {
        checkout debug
      		}
   	 	}

   	 stage('Debug') {
   	 	steps {
   	 	 fastlane release
   	 	}
   	 }		
	}
}