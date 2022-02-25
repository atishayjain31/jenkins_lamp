
  
pipeline {
  agent any
  stages {
    stage('copy to lamp stack server') {
      steps{
              sh 'scp index.html root@35.171.153.38:/var/www/html/index.html'
           }
        }
    }
}
