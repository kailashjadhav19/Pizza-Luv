pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        echo 'My Failed pipeline'
      }
    }
    stage('test') {
      steps {
        maven_invoker(reportsFilenamePattern: '.xml', invokerBuildDir: 'C:\\Users\\Kailash\\Downloads\\Pizza-Luv-master.zip\\Pizza-Luv-master')
      }
    }
  }
}