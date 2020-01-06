pipeline {
    agent any
    stages {
        stage('Fetch') {
            steps {
                bat 'git clone "https://github.com/MichaelWoj/JenkinsAssignment.git"'
            }
        }
        stage('Build') {
            steps {
                 bat 'mvn clean -f "JenkinsAssignment"'
                 bat 'mvn compile -f "JenkinsAssignment"'
            }
        }
	}
}
