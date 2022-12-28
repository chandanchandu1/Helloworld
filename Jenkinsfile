pipeline
{
    agent any
    
    stages
    {
        stage('Git')
        {
            steps
            {
                git 'https://github.com/chandanchandu1/helloworld.git'
            }
        }

        stage('Unit Testing')
        {
            steps
            {
                bat 'mvn test'
            }
        }
    }
}