pipeline
{
    agent any
        stages
        {
            stage('clone')
            {
                steps
                {
                    git branch:'new1',url:'https://github.com/shivanibijjala9-hash/Devops-week1.demo.git'
                }
            }
stage('build')
{
    steps
    {
        sh 'javac Hello.java'
    }
}
stage('run')
{
    steps
{
    sh 'java Hello'
}
}
}
}
