pipeline {
     agent any
         stages {
                stage('one') {
                        steps {
                        echo 'Hi, This is Naveen'
                        }
                      }
          stage('two') {
                steps {
                       input('Do you want to proceed?')
                       }
                      }
          stage('Three') {
                When {
                       not {
                             branch "master"
                             }
                      }
                      steps {
                      echo "hello"
                      }
                   }
