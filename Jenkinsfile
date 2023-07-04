pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            when
            {
                /*tag '2.0'*/
                buildingTag()
            }
            steps
            {
                echo "Building Tag"
            }
        }
    }
}