pipeline {
  agent any
  stages {
    stage('Clone ') {
      steps {
        git(branch: 'main', url: 'https://github.com/mmijden/website-deployment', poll: true)
        sh '''git https://github.com/mmijden/website-deployment

'''
      }
    }

  }
}