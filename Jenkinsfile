pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''dotnet restore
dotnet publish -c release'''
      }
    }
  }
}