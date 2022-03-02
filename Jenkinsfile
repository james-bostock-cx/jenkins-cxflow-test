pipeline {
    agent any
    stages {
      stage ('CxFlow') {
        steps {
          echo 'CxFlow stage'
          bat 'java -jar C:\\CxFlow\\cx-flow-1.6.30-java11.jar --scan --checkmarx.version=9.0 --checkmarx.usernme=cxflow --checkmarx.password=CxFlow1! --checkmarx.team=/CxServer --checkmarx.url=http://localhost --cx-flow.bug-tracker=WAIT'
        }
      }
    }
}
