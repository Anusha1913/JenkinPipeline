pipeline {
	agent none
stages {
	stage ('STAGE1'){
	
		agent {label 'Java'}
	steps {
		sh 'sleep 30'
	     }
	}
	stage ('STAGE2'){
		agent {label 'C'}
	steps {
		sh 'sleep 60'
	     }
	}
}
}
