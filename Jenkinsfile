node {
	
	stage('SCM') {
	// git clone
	git 'https://github.com/khadak-bogati/spring-petclinic.git'
	
	}
	
	stage ('build the packages') {
	// mvn packages
	sh 'mvn clean package'
	
	}
	
	stage ('archival') {
	// archiving artifacts
	archive 'target/*.jar'
	
	}
	
}