pipeline{
	agent any
	stages{
		stage("Run Test"){
			steps{
				sh "docker-compose up"
			}
		}
		stage("Bring Grid Down"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}