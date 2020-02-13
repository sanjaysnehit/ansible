pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        printf("my name is Pranaya")
      }
    }
    stage('dev') {
      parallel {
        stage('dev') {
          agent any
          steps {
            printf("Test")
          
          }
        }
        stage('sandbox') {
          agent any
          steps {
            printf("testing parallel stage")
          }
        }
      }
    }
    stage('123') {
      steps {
        printf("test test")
      }
    }
  }
}
