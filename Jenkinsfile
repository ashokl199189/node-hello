pipeline{
    agent any
    stages{
        stage("checkout") {
            steps{
                git : "https://github.com/ashokl199189/node-hello.git"
            }
        }
        stage("build"){
            steps{
                sh  "npm start"
            }
        }
    }
}
