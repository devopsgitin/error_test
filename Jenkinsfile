pipeline{
  agent any
  stages{
    stage("Check Status"){
      steps{
        sh "bash file.sh $value"
      }
    }
    stage("Stage 2"){
      steps{
        echo "Hello!"
      }
    }
  }
}
