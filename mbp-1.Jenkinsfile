pipeline {

    environment {
        MY_BUILD_NUMBER = VersionNumber(versionNumberString: '${BUILDS_ALL_TIME}')
    }

    stages {
      stage('hi') {
        steps {
          sh "echo hi"
        } 
      }
    }
}

