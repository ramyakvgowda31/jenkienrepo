pipeline {
    agent any
    stages {
        stage ("parallel job") {
            when {
                branch "master"
            }
            parallel {
                stage ('backend'){
                    steps {
                        echo "buliding the backend"
                    }
                }
                stage ('frontend') {
                    steps {
                        echo "bulinding the frontend"
                    }
                }
            }
        }
    }
}

