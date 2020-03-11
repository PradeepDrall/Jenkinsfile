
node { 
	stage('SCM checkout') {
	git 'https://github.com/PradeepDrall/Jenkinsfile.git'
	}
	stage('Compile-Package'){
	// Get maven home path
	def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
	sh "${mvnHome}/bin/mvn package"
	}
}
