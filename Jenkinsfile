withCredentials([usernamePassword(credentialsId: '044eb448-7837-4a5a-a88c-7c78267ab442', passwordVariable: 'passwd', usernameVariable: 'uname')]) {
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
				stage('Deploy')
				{
					steps {
						echo "deploy Successfully"
					}
				}
			}
			}
		}
}
}
