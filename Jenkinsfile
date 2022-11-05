pipeline {
  agent {
    node {
      label 'lab02'
    }

  }
  stages {
    stage('clean') {
      steps {
        sh 'mvn -DskipTests clean'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn -DskipTests compile'
      }
    }

  }
}