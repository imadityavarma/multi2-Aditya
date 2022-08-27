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
                branch "master"
            }
            steps{
                echo "hello aditya"
            }
        }
    }
}
