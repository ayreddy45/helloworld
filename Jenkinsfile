pipeline {
    
    agent any
    
stages {
 stage('Checkout') {
    steps {
     git 'https://github.com/ayreddy45/helloworld.git'
     }
  }

stage('Build'){
   steps{
      bat "call Build.cmd"
    }
 }
    
stage('Publish'){
     steps{
       bat "call Publish.cmd"
     }
  }
 }
}
