pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        nodejs('Node'){
          echo 'Building Application.....'
          sh 'chown -R $(whoami):$(whoami)'
          sh 'npm install'
        }
      }
    }
  }
}
