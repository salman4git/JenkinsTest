pipeline {
	agent any

	stages {
	  stage('Print') {
      steps {
        fastlane debug
      		}
   	 	}

   	 stage('Debug') {
   	 	steps {
   	 	 fastlane release
   	 	}
   	 }		
	}
}