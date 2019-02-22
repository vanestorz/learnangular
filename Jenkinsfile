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
          sh 'ng build --prod'
        }
      }
      stage('Deploy'){
        steps{
          echo "Success!"
        }
      }
    }  
}