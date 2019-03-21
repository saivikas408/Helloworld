pipeline{
	agent any
	stages{
		stage('build') {
 			 steps {
  			  echo 'BUILD successful'
			}
		}
		stage('Test') {
 			 steps {
  			  echo 'TEST successful'
			}
		}
		stage('Deploy - DEV') {
 			 steps {
				if {
					branch 'dev'
				}
  			  echo 'dev DEPLOY successful'
			}
		}
		stage('Deploy - PROD') {
 			 steps {
				if {
					branch 'prod'
				}
  			  echo 'prod DEPLOY successful'
			}
		}
	}
}
