pipeline{
	agent any
		stages
		{
		stage('run test'){
		 parallel{
				stage('Build') {
						steps{
							echo "Built successfully"
						}
				}
				stage('Test') {
					steps {
						echo "Test Successfully"
					}
				}
				
			}
			}
		}
}
