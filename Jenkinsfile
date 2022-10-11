pipeline {
  agent any
  stages {
    stage('Clone from Git repository') {
      steps {
        git 'https://github.com/LeNgocMinh2704/jenkin-github.git'

      }
    }
    stage('build'){
        node{
      checkout scm
      sh 'mvn clean install'
}
    }

  }
}
