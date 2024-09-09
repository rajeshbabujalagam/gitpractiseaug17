pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload_main')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild_main')
        {
            steps
            {
                sh 'mvn package'
            }
        }
        
	}

}
