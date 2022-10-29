pipeline{
  agent any
  stages{
    stage("Check Status"){
      steps{
        sh "bash file.sh $value"
      }
    }
    stage("Status"){
      steps{
        sh "bash stats.sh $value"
      }
    }
  }
}
