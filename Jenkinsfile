
node { 
	stage('SCM checkout') {
	git 'https://github.com/PradeepDrall/Jenkinsfile.git'
	}
	stage('Compile-Package'){
	// Get maven home path	
	mvn clean package
	}
}
