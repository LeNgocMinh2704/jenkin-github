pipeline {
  agent any
  stages {
    stage('Clone from Git repository') {
      steps {
        git 'https://github.com/LeNgocMinh2704/jenkin-github.git'

      }
    }
     stage('Build from Git repository') {
        steps{
          echo "Build"
      }
    }
    stage('Deploy '){
        steps{
          echo "Deploy"
      }
    }
    stage('Test '){
        steps{
          echo "Test"
      }
    }
    stage('Test UI'){
        steps{
          echo "Test UI"
      }
    }
    stage('Test funcation B'){
        steps{
          echo "Test B"
      }
    }
    stage('Test funcation C'){
        steps{
          echo "Test C"
      }
    }
    stage('Release '){
        steps{
          echo "Release"
      }
    }

  }
}
