pipeline{
  agent any
  triggers {
  cron '* * * * *'
    }
  stages{
    stage('Build'){
      steps{
        nodejs('Node'){
          echo 'Building Application.....'
          sh 'npm install'
        }
      }
    }
  }
}
