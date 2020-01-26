pipeline {
  agent none
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'My Failed pipeline'
          }
        }
        stage('1st stage') {
          steps {
            echo 'this is 1st stage'
          }
        }
      }
    }
    stage('test') {
      steps {
        maven_invoker(reportsFilenamePattern: '.xml', invokerBuildDir: 'C:\\Users\\Kailash\\Downloads\\Pizza-Luv-master.zip\\Pizza-Luv-master')
      }
    }
  }
}