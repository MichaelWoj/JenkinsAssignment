pipeline
{
    agent any
    stages
    {
        stage('FetchStage')
        {
            steps
            {
                git 'https://github.com/MichaelWoj/JenkinsAssignment'
            }
        }
        stage('BuildStage') { 
            steps {
                bat 'javac -cp junit-4.13.jar; Student.java studentTest.java'
            }
        }    
    }
}
