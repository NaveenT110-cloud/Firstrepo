pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi,welcome to GIT'
                 }
                 }
                 stage('Two') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 stage('Three') {
                 when {
                       not {
                            branch "master"
                       }
                 }
                 steps {
                       echo "Finished"
                 }
                 }
         }
}
