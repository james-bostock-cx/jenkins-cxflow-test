pipeline {
    agent any
    stages {
      stage ('CxFlow') {
        steps {
          echo 'CxFlow stage'
          bat 'java -jar C:\\CxFlow\\cx-flow-1.6.30-java11.jar --scan --f=. --checkmarx.version=9.0 --checkmarx.username=cxflow --checkmarx.password=CxFlow#123 --checkmarx.team=/CxServer --checkmarx.base-url=http://localhost --cx-flow.bug-tracker=WAIT --app=Test --cx-project=monash-test-declarative-pipeline'
        }
      }
    }
}
