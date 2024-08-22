pipelne {
   agent any
  
    stages {
             stage('Master') {
                     steps {
                           sh 'eco "This is master branch"'
                     }
            }
              stage('sprint1')  {
                      steps {
                           sh 'echo "this is sprint1 branch... modified"'
                     }
             }
             stage("Development") {
                        steps {
	            sh 'echo "Deploying application..."'
	     }
             }
         }
 }
       
