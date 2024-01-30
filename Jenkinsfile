pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo payload
            }
        }
        stage('execute python'){
        
            steps{
                script{
                    sh("python3 helloworld.py")
                }
            }        
        }
    }
}
