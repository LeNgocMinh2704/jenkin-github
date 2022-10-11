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
    stage('Tesing '){
        steps{
          echo "Testing"
      }
    }

  }
}
