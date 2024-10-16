pipeline {
	agent any

	stages {
		stage("Build") {
			steps {
				myNewFunction('Build2')
				
			}
		}
		stage("Test") {
			steps {
				myNewFunction('Test2')
				
			}
		}
		stage("Deploy") {
			steps {
				myNewFunction('Deploy2')
				
			}
		}
	}
}

def myNewFunction(String text){
	echo "Krok: ${text}"
}
