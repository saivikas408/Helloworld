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
				when { branch 'dev' }			
				echo 'DEV DEPLOY successful'
			}
  			  
		}
		stage('Deploy - PROD') {
 			 steps {
				when { branch 'prod' }			
				echo 'PROD DEPLOY successful'
			}
  			  
		}
	}
}
