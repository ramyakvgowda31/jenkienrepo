pipeline {
  agent none
  stages{
    stage ('build and run') {
      parallel {
        stage ('master-agent-parallel'){
          agent {label 'master'}
          steps {
            echo "build"
          }
        }
        stage ("test") {
          steps{
          echo "test"
        }
        }
      }
    }
