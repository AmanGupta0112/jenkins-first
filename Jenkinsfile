pipeline {
	agent {
		docker { image 'python:3.11.9-alpine3.19'  }
	}
	stages {
		stage('TEST') {
			steps {
				sh 'python3 --version'
			}
		}
	}
}
