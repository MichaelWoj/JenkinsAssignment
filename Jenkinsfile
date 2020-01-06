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
                 sh 'mvn clean -f "student-attendance-jenkins"'
                 sh 'mvn compile -f "student-attendance-jenkins"'
            }
        }
	}
}