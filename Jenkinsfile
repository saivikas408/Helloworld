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
				when {
					allOf {
					branch 'dev'
					}
				}
  			  echo 'dev DEPLOY successful'
			}
		}
		stage('Deploy - PROD') {
 			 steps {
				when {
					allOf {
					branch 'prod'
					}
				}
  			  echo 'prod DEPLOY successful'
			}
		}
	}
}
