pipeline {
  agent any
 
  tools {
      nodejs "node"
  }
  
  stages {
      stage('Console Hello World') {
          steps {
            input message: 'Are you approve to continue ?', submitter: 'kimjaeha'
          }
      }
      stage('cmd'){
          steps{
            //   bat 'copy /Y .\\jenkins.xml ..\\..\\'
            //   bat 'cd C:\\Program Files (x86)\\Jenkins\\ && type .\\jenkins.xml'
              bat 'copy /Y .\\favicon.ico ..\\..\\war\\'
              bat 'copy /Y .\\*.png ..\\..\\war\\images\\'
          }
      }
  }
}