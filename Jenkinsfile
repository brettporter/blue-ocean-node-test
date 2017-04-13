pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        nodejs(nodeJSInstallationName: 'Node 6.x', configId: '19a65b40-d54b-4a4e-a73f-c6d1f93268c6') {
          sh 'echo $PATH'
        }
        
      }
    }
  }
  tools {
    nodejs 'Node 6.x'
  }
}