pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Build\') {
            steps {
                echo \'Building..\'
            }
        }
        stage(\'Test\') {
            steps {
                echo \'Testing..\'
            }
        }
        stage(\'Deploy\') {
            steps {
                echo \'Deploying....\'
            }
        }
    }
}'''
        }
      }

    }
  }