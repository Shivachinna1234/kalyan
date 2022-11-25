node {

    stage('Gitclone') {
        git branch: 'main', credentialsId: 'sunitha', url: 'https://github.com/Shivachinna1234/kalyan.git'
	   
	}   
	stage('java version') {
	
	       sh 'java -version'
	}
	stage('maven version') {
	
	       sh 'mvn --version'
	}
	stage('maven validate') {
	
	       sh 'mvn validate'
	}
	stage('maven compile') {
	
	       sh 'mvn compile'
	}
	satge('maven test') {
	
	       sh 'mvn test'
	}
	stage('maven package') {
	
	       sh 'mvn package'
	}
}	
