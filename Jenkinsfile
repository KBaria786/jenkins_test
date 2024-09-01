pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        sh "echo building"
      }
    }
    
    stage("test") {
      steps {
        sh "echo testing"
      }
    }
    
    stage("build") {
      steps {
        sh "echo deploy"
      }
    }
  }
}
