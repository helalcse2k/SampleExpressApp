pipeline{
  agent any

  stages{
    stage('Build'){
      steps{
        nodejs('nodejs'){
          echo 'Building Application.....'
          sh 'npm install'
        }
      }
    }
  }
}
