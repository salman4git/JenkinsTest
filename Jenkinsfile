pipeline {
	agent any

	stages {
	  stage('Print') {
      steps {
        sh 'fastlane debug'
      		}
   	 	}

   	 stage('Debug') {
   	 	steps {
   	 	sh 'fastlane release'
   	 	}
   	 }		
}