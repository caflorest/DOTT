pipeline {
	agent any
  stages {
      stage("Test Echo") {
        steps {
          echo "Hello DevOps Academy is this my first CI Project"
        }
      }

      stage("Git cloneee") {
        steps {
          git url: 'https://github.com/caflorest/DOTT.git'
        }
      }
	  stage('test') {
		  steps {
			  sh "mvn clean compile test"
		  }
	  }
	  }
    }
