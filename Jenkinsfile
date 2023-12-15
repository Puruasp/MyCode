pipline {
    agent any 
     stages {
         stage ('Hello') {
             steps {
                bat 'hello world'
                echo "build number is " $ { currentBuild.number}
                
             }
         }

     } 
}