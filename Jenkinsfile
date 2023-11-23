pipeline {
    agent any
    
    stages {
        stage ('check files') {
            steps {
                sh 'ls -la'
            }
        }
         stage ('read file') {
             steps {
                 sh 'cat hello-world.txt'
             }
         }
         stage ('create tarball') {
             steps {
                 sh 'tar -cvf project01.tar *'
             }
         }  
        }
}
