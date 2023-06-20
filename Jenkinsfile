pipeline {
    agent any
environment {
  fname = "kkbd"
  sname = "jkdh"
}

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                
                echo 'Hi world'
                script{
                    sh '/test.sh $fname $sname'
                    
                }
            }
        }
    }
}
