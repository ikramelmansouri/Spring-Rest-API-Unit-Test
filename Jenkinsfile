pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh 'mvn clear compile'
      }
    }

    stage('step2') {
      steps {
        sh 'mvn test'
      }
    }

    stage('step3') {
      steps {
        sh 'mvn clean package'
      }
    }

  }
}