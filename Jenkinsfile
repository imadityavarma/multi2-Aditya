pipeline{
    agent any
    stages{
        stage("maven"){
            when {
                branch "aditydev"
            }
            steps{
                sh "mvn package"
            }
        }
        stage("deploy to prod"){
            when {
                branch "main"
            }
            steps{
                echo "hello aditya"
            }
        }
    }
}
