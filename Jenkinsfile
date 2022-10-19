pipeline {
    agent any

    stages {
    	stage('Git Checkout') {
            steps {
		git branch: 'main', url: 'https://github.com/RohithSingirikonda/demo-counter-app.git'
	    }
        }
	
    	stage('mvn install') {
            steps {
	    	sh 'mvn clean install'
	    }
	}
    }
}

