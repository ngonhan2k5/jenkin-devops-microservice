//SCRIPTED

//DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
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
			echo "Cool"
		}

		success {
			echo "Run when success"
		}

		failure {
			echo "Run when fail"
		}
	}
		
}
