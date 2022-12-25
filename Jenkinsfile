pipeline {
 agent any
 stages {
  stage ("python") {
     steps {
       sh "source /var/lib/jenkins/workspace/pip/env/bin/activate"
     }
   }
   stage ("joke") {
     steps {
       sh "python joke.py"
     }
   }
 }
}
