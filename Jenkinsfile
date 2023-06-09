pipeline {
    agent any

    stages {
        stage ('AZ Group Created') {
            steps {
                script {
                    sh 'az group create -n Fabio-RG --location northeurope'
                    echo 'Resource Group Completed'
                }    
            }
        }

        stage ('AZ VM Created') {
            steps {
                script {
                    sh 'az vm create -n Fabio-Linux -g Fabio-RG --image UbuntuLTS --data-disk-sizes-gb 10 20'
                    echo 'VM Completed'
                }
            }
        }
    }
}
