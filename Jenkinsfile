pipeline {
    agent any


    stages {
      stage('Pull Request') {
        // only run when pull requests
        // fill in code
        steps {
          build job: 'pr', parameters: [string(name: 'FEATURE_BRANCH', value: "")]
        }
      }
      
    }
}
