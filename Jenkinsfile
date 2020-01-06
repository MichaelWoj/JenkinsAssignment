pipeline {
    agent any
    stages {
        stage('Fetch') {
            steps {
                sh 'git clone "https://github.com/MichaelWoj/JenkinsAssignment.git"'
            }
        }
        stage('Build') {
            steps {
                 sh 'mvn clean -f "JenkinsAssignment"'
                 sh 'mvn compile -f "JenkinsAssignment"'
            }
        }
	}
}
