pipeline {
  agent any
  stages {
    stage('commit') {
      steps {
        echo 'commit the code'
      }
    }

    stage('build') {
      steps {
        echo 'build the code'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test the'
          }
        }

        stage('stage') {
          steps {
            echo 'stage'
          }
        }

        stage('deploy') {
          steps {
            echo 'deplot th'
          }
        }

        stage('operate') {
          steps {
            echo 'operate te app'
          }
        }

      }
    }

  }
}