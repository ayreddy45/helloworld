pipeline {
    
    agent any
    
stages {
 stage('Checkout') {
    steps {
     git 'https://github.com/Kabi16/dotnethelloworld.git'
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
