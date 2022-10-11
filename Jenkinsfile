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
    stage('Test funcation A'){
        steps{
          echo "Test A"
      }
    }
    stage('Test funcation B'){
        steps{
          echo "Test B"
      }
    }
    stage('Release '){
        steps{
          echo "Release"
      }
    }

  }
}
