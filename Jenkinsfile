pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        script { 
        if (env.BRANCH_NAME == "master") {
          sh 'echo "master"'
        } 
        if (env.BRANCH_NAME == "develop") {
          sh 'echo "develop"'
        } 
        if (env.BRANCH_NAME == "release") {
          sh 'echo "release"'
        } 
       }
      }
    }
  }
}

