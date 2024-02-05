pipeline {
  stages {  // Define the individual processes, or stages, of your CI pipeline
    stage('Setup') { // Install any dependencies you need to perform testing
      steps {
        script {
          sh """
          pip install -r requirements.txt
          """
        }
      }
    }
   }

 }
