pipelne {
   agent any
  
    stages {
             stage('Master') {
                     steps {
                           sh 'eco "This is master branch modified"'
                     }
            }
              stage('sprint1')  {
                      steps {
                           sh 'echo "sprint1 application ..."'
                     }
             }
             stage("Development") {
                        steps {
	            sh 'echo "Deploying application..."'
	     }
             }
         }
 }
       
