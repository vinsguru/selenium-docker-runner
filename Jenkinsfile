pipeline{
	agent any
	stages{
		stage("Run Test"){
			steps{
				sh "docker-compose up --no-color"
			}
		}
		stage("Bring Grid Down"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}