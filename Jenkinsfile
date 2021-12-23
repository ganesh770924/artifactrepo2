pipeline{
  agent any
  stages{
    stage('artifact stage'){
      steps{
        archieveartifact artifacts: "output.txt" ,fingerprint=true
      }
    }
  }
}
