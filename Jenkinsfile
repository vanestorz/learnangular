pipeline{
  agent any
  tools {nodejs "node"}
  stages{
    node{
      stage('SCM Checkout'){
        git 'https://github.com/vanestorz/learnangular'
      }
      stage('Prepare Environment'){
        git branch:'master',url:'https://github.com/vanestorz/learnangular'
        sh 'npm install'
      }
      stage('Build'){
        echo "Success!"
      }
      stage('Deploy'){
        echo "Success!"
      }
    }
  }
}