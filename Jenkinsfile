pipeline{
  agent any
  tools {nodejs "node"}
    stages{
      stage('Prepare Environment'){
        steps{
          git branch:'master',url:'https://github.com/vanestorz/learnangular'
          sh 'npm install'
        }
      }
      stage('Build'){
        steps{
          echo "Success!"
        }
      }
      stage('Deploy'){
        steps{
          echo "Success!"
        }
      }
    }  
}