pipeline{

	agent any
	stages{
		stage("compile"){
		steps{ 
			sh 'javac Test.java'
		}
	
	}
	stage("Run"){
		steps{
			sh 'java Test.java'
		}
	}
	}
}
