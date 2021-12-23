pipeline{
  agent any
  stages{
    stage('artifact stage'){
      steps{
        archiveArtifacts artifacts: 'output.txt' ,fingerprint=true
      }
    }
  }
}
