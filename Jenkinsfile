pipeline
{
    agent any
    stages
    {
        stage('ContDownload')
        {
            steps
            {
                git 'https://github.com/GPRAKASHG/prakash_multibranch.git'
            }
        }
        stage('ContBuild')
        {
            steps
            {
                sh 'mvn package'
            }
        }
