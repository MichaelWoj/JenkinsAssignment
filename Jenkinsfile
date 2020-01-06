pipeline {
    agent any
    stages {
        stage('Fetch') {
            steps {
                git url: 'https://github.com/MichaelWoj/JenkinsAssignment.git'
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
