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
			when { branch 'dev' }			
 			 steps {
				echo 'DEV DEPLOY successful'
			}
  			  
		}
		stage('Deploy - PROD') {
			when { branch 'prod' }
 			 steps {			
				echo 'PROD DEPLOY successful'
			}
  			  
		
	}
}
