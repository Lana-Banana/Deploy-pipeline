pipeline {
  agent any
  stages {
    stage('Artifact Fetch') {
      steps {
        echo 'Fetch Artifact From Storage or Repositories...'
      }
    }

    stage('Manifest Rendering') {
      steps {
        echo 'Redering Manifests yaml file from Artifacts'
      }
    }

    stage('K8S Cluster') {
      steps {
        echo 'Select K8S Cluster'
        echo 'Integration with Public Cloud Provider'
      }
    }

    stage('Deploy Strategy') {
      steps {
        echo 'Blue-Green'
        echo 'Canary'
        echo 'Recreate'
        echo 'Rolling Update'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}