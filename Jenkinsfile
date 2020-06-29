pipeline {
  agent any
 
  tools {
      nodejs "node"
  }
  
  stages {
      stage('Code Quality') {
        steps {
          osfBuilderSuiteStandaloneSonarLinter reportPath: 'sonar-reports', sourcePatterns: [[excludePatterns: [[excludePattern: '**/**.css']], sourcePattern: '**/**.js']]
        }
      }
      // stage('Console Hello World') {
      //     steps {
      //       input message: 'Are you approve to continue ?', submitter: 'kimjaeha'
      //     }
      // }
      // stage('cmd'){
      //     steps{
      //       //   bat 'copy /Y .\\jenkins.xml ..\\..\\'
      //       //   bat 'cd C:\\Program Files (x86)\\Jenkins\\ && type .\\jenkins.xml'
      //         bat 'copy /Y .\\images\\favicon.ico ..\\..\\war\\'
      //         bat 'copy /Y .\\images\\*.png ..\\..\\war\\images\\'
      //         bat 'copy /Y .\\images\\jenkins.svg ..\\..\\war\\images\\'
      //     }
      // }
  }
}