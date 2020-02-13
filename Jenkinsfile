pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        print("my name is Pranaya")
      }
    }
    stage('dev') {
      parallel {
        stage('dev') {
          agent any
          steps {
            print("Test")
          
          }
        }
        stage('sandbox') {
          agent any
          steps {
            print("testing parallel stage")
          }
        }
      }
    }
    stage('123') {
      steps {
        print("test test")
      }
    }
  }
}
