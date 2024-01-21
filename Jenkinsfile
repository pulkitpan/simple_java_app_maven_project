pipeline
{
    agent any
    stages
    {
        stage('fetch')
        {
            steps{
            git 'https://github.com/pulkitpan/simple-java-maven-app.git'
            }
        }
        
        stage('build')
        {
            steps{
             build 'simple-java-maven-app'
            }
        }
        stage('Test')
        {
            steps{
            echo "Testing..Phase"
            }
        }
        stage('Deploy')
        {
            steps{
            echo 'Deploying..Phase'
            }
        }
    }
}
