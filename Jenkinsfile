pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is samara 
                  }
            }
            stage('Testing') {
                  steps {
                        echo "unit testing"
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage(' Auto Testing') {
                  steps {
                        echo "testing Area"
                  }
            }      
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
