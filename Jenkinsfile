@Library('shared-lib') 
pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        script{
          buildApp()
        }
      }
    }
  }
}
