pipeline {
    agent any

    stage {

        stage ('Build Docker Image')
            steps {
                script {
                    dockerapp = docker.build("thiagor402/kube-news:${env.BUILD_ID}", "-f ./src/Dockerfile ./src")
                }
            }
    }

}