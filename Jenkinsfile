pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Build world'
            }
        }
        stage ('Deploy'){
            steps {
                echo 'Build world'
                    }
        }
        stage('Test') {
              steps { 
                  echo 'Deploy World'
              }
           }
      }
    post
    {
      always
      {
      emailext body:'Summary', subject: 'Pipeline Status', to: 'basu007raj@gmail.com'
      }
    }
  }  
