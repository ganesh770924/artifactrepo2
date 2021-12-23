pipeline{
  agent any
  stages{
    stage('artifact stage'){
      steps{
        archieveArtifact artifacts: "output.txt" ,fingerprint=true
      }
    }
  }
}
