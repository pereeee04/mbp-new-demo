pipeline{
  agent any
  stages{
    stage("Hello"){
      steps{
        echo "this is mbp"
      }
    }
    stage("Hello"){
      steps{
        when{
          branch "develop"
        }
      }
    }
  }
}
