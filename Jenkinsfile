pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        cleanWs(cleanWhenAborted: true, cleanWhenFailure: true, cleanWhenNotBuilt: true, cleanWhenSuccess: true, cleanWhenUnstable: true, cleanupMatrixParent: true, deleteDirs: true)
        bat 'C:\\kituri\\Maven\\apache-maven-3.5.2\\bin\\mvn test'
      }
    }
  }
}