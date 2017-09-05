pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh "id"
				sh 'make peer-docker'
				echo 'Building..'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}
	}
}