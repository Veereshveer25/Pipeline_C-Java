pipeline {
	agent none
 
	stages {
		stage ('STAGE 1') {
			   agent { label 'node1_test_c'}
			steps {
				echo 'This is slaveforc node with STAGE 1'
				sh 'sleep 10'
			}	
		}
		stage ('STAGE 2') {
				agent { label 'node2'}
			steps {
				echo 'This is slaveforjava with STAGE 2'
				sh 'sleep 10'
			}	
		}
		
	}
}
