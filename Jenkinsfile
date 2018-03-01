pipeline {
  agent {
    docker {
      image 'maven:3.39-jdk-8'
      args 'sudo yum install maven'
    }
    
  }
  stages {
    stage('init') {
      steps {
        echo 'yahoo'
      }
    }
  }
}