pipeline {
    agent none

    stages {
        stage('Hello') {
            agent { label 'Slave_Two' }
            steps {
                echo 'Hello World'
                sh '''
                    ls -lrt
                '''
            }
        }

        stage('Hello2') {
            agent { label 'Slave_One' }
            steps {
                echo 'Hello World 2'
            }
        }

        stage('Hello3') {
            agent { label 'Slave_Two' }
            steps {
                echo 'Hello World 3'
            }
        }
    }
}
