pipeline {
 agent any
 stages {
  stage ("python") {
     steps {
       bat "python3 --version"
     }
   }
   stage ("joke") {
     steps {
       bat "python joke.py"
     }
   }
 }
}
