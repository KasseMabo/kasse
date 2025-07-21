pipeline {
    agent {label 'docker'}

    stages{
        stage('Build'){
            steps{
                script{
                    sh 'Hello UADB'
                }
            }

        }
    }

    // environment {
    //     DOCKER_PASSWORD=credentials('DOCKER_PASSWORD')
    // }

    // stages {
    //     stage('Docker login') {
    //         steps {
    //             script {
    //                 sh 'echo $DOCKER_PASSWORD | docker login -u abdoukasse --password-stdin'
    //             }
    //         }
    //     }

        // stage('Docker build image') {
        //     steps {
        //         script {
        //             sh 'docker build -t uadb:v1 .'
        //         }
        //     }
        // }

        // stage('Docker tag image') {
        //     steps {
        //         script {
        //             sh 'docker tag uadb:v1 YourUSername/uadb:v1'
        //         }
        //     }
        // }

        // stage('Docker push image') {
        //     steps {
        //         script {
        //             sh 'docker push YourUSername/uadb:v1'
        //         }
        //     }
        // }
}