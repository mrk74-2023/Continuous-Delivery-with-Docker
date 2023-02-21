pipeline {
     agent any
     stages {
          stage("Code coverage") {
               steps {
                    sh "./gradlew jacocoTestCoverageVerification"
               }
          }
     }
}
