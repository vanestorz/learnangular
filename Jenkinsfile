pipeline{
  agent any
  tools {nodejs "node"}
  node{
    stage('SCM Checkout'){
      checkout scm
    }
  }
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