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
                           sh 'echo "this is sprint1 branch..."'
                     }
             }
             stage("sprint2") {
                        steps {
	            sh 'echo "this is sprint2 branch... modified"'
	     }
             }
         }
 }
       
