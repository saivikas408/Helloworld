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
				echo 'dev DEPLOY successful'
			}
  			  
		}
	}
}
