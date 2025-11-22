pipeline
{
    agent any

    tools
    {
        maven 'Maven_3.9.9'
    }

    stages
    {
        stage('Checkout Code from GitHub')
        {
            steps()
            {
                git branch: 'DevOpsJulyBatch', url: 'https://github.com/MithunTechnologiesDevOps/maven-web-application.git'
            }
        }

        stage('Build Artifact')
        {
            steps()
            {
                sh 'mvn clean package'
            }
        }
    }
}