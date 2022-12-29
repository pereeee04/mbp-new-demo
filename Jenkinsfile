pipeline{
  agent any
  stages{
    stage("Hello"){
      steps{
        echo "this is multi branch pipeline"
        }
      }
    stages{
      stage("Hello"){
        When{
          branch "develop"
          }
        }
      }
    }
  }
