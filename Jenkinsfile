pipeline{
  agent any
  stages{
    stage("Hello"){
      steps{
        echo "this is multi branch pipeline"
        }
      }
     stage("Hello"){
       When{
         branch "develop"
         }
       }
     }
   }
