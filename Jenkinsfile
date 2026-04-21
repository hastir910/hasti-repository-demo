pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git 'https://github.com/hastir910/hasti-repository-demo'
      }
    }

    stage('Build') {
      steps {
        bat 'pip install pytest'
      }
    }

    stage('Test') {
      steps {
        bat 'pytest'
      }
    }

  }
}