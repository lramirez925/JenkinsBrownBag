pipeline {
  agent {
    docker {
      image 'ortussolutions/commandbox'
      args '-u root'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'In Build Step\''
      }
    }
  }
}