pipeline {
     agent any
     stages {
         stage('Build') {
             steps {
                 echo 'Building... 123'
             }
             post {
                 always {
                     jiraSendBuildInfo() 
                 }
             }
         }
     }
 }
