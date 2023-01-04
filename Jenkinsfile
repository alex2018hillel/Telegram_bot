pipeline {
 agent any
 stages {
  stage ("python") {
     steps {
       bat "python --version"
     }
   }
   stage ("joke") {
     steps {
       bat "python joke.py"
     }
   }
 }
}
