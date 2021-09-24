pipeline {

    agent { label 'node-1'}

    stages {

        stage("Build") {
            steps {
                echo "Buiding an application..."
            }
        }

        stage("Test") {
            steps {
                echi "Testing an application..."
            }
        }

        stage("Deploy") {
            steps {
                echo "Deploying an application..."
            }
        }

    }
}
