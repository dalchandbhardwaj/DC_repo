pipeline {
  agent any
  stages {
    stage('Build ') {
      steps {
        sh '''pwd

date
ls
'''
      }
    }

    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'Hi this is for Test'
          }
        }

        stage('Test Check it self ') {
          steps {
            echo 'Hi this checking from manish side '
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Time to deploy'
      }
    }

    stage('Deployment Success') {
      steps {
        echo 'It is deploy Successfully '
      }
    }

    stage('Sleep') {
      steps {
        sleep 10
      }
    }

    stage('Again Deploye Test') {
      steps {
        sh '''pwd
'''
      }
    }

    stage('Test Succesfull') {
      steps {
        echo 'Every Test is succesfull'
      }
    }

  }
}