pipeline {
	agent any
	    stages{
		stage ('Build') {
		  	steps{
			 sh '/home/saad/Documents/apache-maven-3.6.0/bin/mvn installation propre' 
			}
		}
		stage ('Test') {
			steps{
			sh '/home/saad/Documents/apache-maven-3.6.0/bin/mvn test'
			}
		}
		}
}
