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
                bat 'javac Student.java'
            }
        }

	}
}
