pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is samara '
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
             stage('Test') {
                   steps {
                        echo "Testing Area" 
                   }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}         
