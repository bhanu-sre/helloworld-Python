pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
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
