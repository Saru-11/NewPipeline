pipeline
{
    agent any


stage
{
    stage('Checkout')
{

steps
{
    git URL 'https://github.com/Saru-11/NewPipeline', branch:main
}



stage('Build')
{
    steps
    {
        script
        {
            def javaFiles = sh '-cp C:/Users/saru_/Documents/Maven_Project _TestNG/test1/demo/src/test/java/com/example/Example.java'
            sh "Javac ${Javafiles}"
        }
    }
}

    stage('Run')
    {
        steps{sh 'java -cp C:/Users/saru_/Documents/Maven_Project _TestNG/test1/demo/src/test/java/com/example/Example.java'}
    }
}}}

