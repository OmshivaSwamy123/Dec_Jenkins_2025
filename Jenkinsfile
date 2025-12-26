pipeline 
{
    agent any

    stages 
    {
        stage('Hello') 
        {
            steps 
            {
                echo 'Hello World'
				sh '''
					ls -lrt
				   '''
            }
        }
        stage('Hello2') 
        {
            steps 
            {
                echo 'Hello World 2'
            }
        }
		stage(Hello3)
		{
			steps
			{
				echo 'Hello World 3'
			}
		}
    }
}
