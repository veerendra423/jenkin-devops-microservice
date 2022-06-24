pipeline{
	agent any
	stages{
		stage("Build"){
			steps{
				echo "Build"
			}
		}
		stage("Test"){
			steps{
				echo "Test"
			}
		}
		stage("Integration Test"){
			steps{
				echo "Integration test"
			}
		}
	}
	post{
		always{
			echo 'I always run'
		}
		success{
			echo 'I run when you are success'
		}
		failure{
			echo 'I will run when you fail'
		}
	}
}
