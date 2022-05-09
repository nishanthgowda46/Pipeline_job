pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh '''
						echo "STAGE 1: This is a build stage"
						sleep 2
				   ''' 
            }
        }
        stage('Deploy') { 
            steps {
                sh '''
						echo "STAGE 2: This is a deploy stage"
						sleep 5
                   '''
		    }
        }
        stage('Test') { 
            steps {
                sh '''
						echo "STAGE 3: This is a test stage"
				   '''
            }
        }
    }
}
