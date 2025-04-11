pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh "pip install -r app/requirements.txt"
            }
            
        }
        stage("test"){
            steps{
                sh "python3 helloworld.py"
            }
        }
    }

}