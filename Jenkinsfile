pipeline {
 agent any
 stages {
  stage ("python") {
     steps {
       sh "python3 --version"
     }
   }
   stage ("joke") {
     steps {
       sh "python joke.py"
     }
   }
 }
}
