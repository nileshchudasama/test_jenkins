pipeline{
	agent any
		stages
		{
		stage('run test'){
		 parallel{
				stage('Build stage') {
						steps{
							echo "Built successfully"
						}
				}
				stage('Testing stage') {
					steps {
						echo "Test Successfully"
					}
				}
				stage('Deploy stage')
				{
					steps {
						echo "deploy Successfully"
					}
				}
			}
			}
		}
}
