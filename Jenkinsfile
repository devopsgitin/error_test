pipeline{
  agent any
  stages{
    stage("Check Status"){
      step{
        sh "bash file.sh $value"
      }
    }
    stage("Stage2"){
      step{
        echo 'Hello!'
      }
    }
  }
}
