pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        nodejs('Node'){
          echo 'Building Application.....'
          sh 'npm install'
        }
      }
    }

    stage('Test'){
      steps{
        nodejs('Node'){
          echo 'Testing Application.....'
          sh 'npm test'
        }
      }
    }
  }
}
