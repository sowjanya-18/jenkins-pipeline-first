pipeline {
  agent any
  stages {
    stage('buzz-build') {
      steps {
        echo 'hi this sowji'
        archiveArtifacts(fingerprint: true, artifacts: '.txt')
      }
    }

    stage('buzz-test') {
      steps {
        echo 'hi this bhaskar'
      }
    }

    stage('buzz-deploy') {
      steps {
        echo 'this is sowji learing jenkins'
      }
    }

  }
}