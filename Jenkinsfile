/* node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo "Integration Test"
	}
}
*/

pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
			echo "Build"
			}
		}
		stage('Test'){
			steps {
			echo "Test"
		}
		}
		stage('Integration Test') {
			steps {
			echo "Integration Test"
		}
		}
		} 
		post {
			always {
				echo "This run always nel post build"
			}
			success {
				echo "this run on success"
			}
			failure {
				echo "This run on fail"
			}
		}	
		}
