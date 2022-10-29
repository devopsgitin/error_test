pipeline{
  agent any
  stage{
    stages("Check Status"){
      steps{
        sh "bash file.sh $value"
      }
    }
    stages("Stage2"){
      steps{
        echo 'Hello!'
      }
    }
  }
}
