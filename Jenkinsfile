pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh "cd app && pip install -r requirements.txt"
            }
            
        }
        stage("test"){
            steps{
                sh "python3 helloworld.py"
            }
        }
    }

}