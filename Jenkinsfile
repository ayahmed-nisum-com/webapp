//Declarative //
pipeline {
	agent any
	
	stages{
	stage('Build'){
		steps{
		sh "${MAVEN_G+HOME}/bin/mvn clean package"
		}
	}
	stage('Test'){
		steps{
		echo 'testing..'
		}
	}
	stage('Deploy'){
		steps{
		echo 'Deploying..'
		}
	}
}
}
