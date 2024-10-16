pipeline {
	agent any

	stages {
		stage("Build") {
			steps {
				myNewFunction('Build')
				
			}
		}
		stage("Test") {
			steps {
				myNewFunction('Test')
				
			}
		}
		stage("Deploy") {
			steps {
				myNewFunction('Deploy')
				
			}
		}
	}
}

def myNewFunction(String text){
	echo "Krok: ${text}"
}