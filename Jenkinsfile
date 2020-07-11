pipeline {
    agent any
    stages {
        stage('Build') {
            
            }  
      steps {
        sh 'python3 sources/add2vals.py sources/calc.py'
        stash(name: 'compiled-results', includes: 'sources/*.py*')
      }
    }
   }
}
